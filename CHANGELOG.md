# Changelog 

# version 3.0
- initial version of the template based on the OSLO toolchain 3.0
- make version value according to semver.

# version 3.0.1
- make ea-to-rdf extraction logs more readible
- halt on error in ea-to-rdf extraction process.
- publish translation support files

# version 3.0.2
- fix the upgrade_config.sh script to not change the configuration when the configuration contains a valid translation block.

# version 3.0.3
- add documentation on the Docker images used
- version fix the Docker images
- re-iniate template variable in CircleCI config
- add xsd generation configuration 
- add extra message in case downloading from GitHub fails
- fix mapping for vocabulary definition

# version 3.0.4
- upgrading configs from toolchain 2.0 to toolchain 3.0 bugfix
- html-renderer: bugfix, language aware title in translation config block is taken into account.

# version 3.0.5
- add scripts to validate the presence of each publication point in the generated repository
- integrate the scripts in the last step of CircleCI artefact_create
- make triggerall option to rebuild only the changed publication points when switched off
- fix issues with English vocabulary template 
- fix external dependency failure of ruby tool linkeddata by bumping the ruby image version 
