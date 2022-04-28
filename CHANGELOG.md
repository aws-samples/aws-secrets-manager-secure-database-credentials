## [1.0.2] - 2022-04-28
### Changed
- Updated license type to be MIT License

## [1.0.1] - 2022-04-21
### Added
- CHANGELOG.md file
- LICENSE.md file
- NOTICE.md file 
- IMPLEMENTATION.md file 
### Changed
- Updated README.md file to include results from a securtiy scan using [Bandit](https://bandit.readthedocs.io/en/latest/)

## [1.0.0] - 2022-04-14
### Changed
Minor changes to the original blog codebase are shown below
- upgrade lambda python runtime version - version used in the old blog is not supported anymore
- upgrade the python dependencies and update the code to use the updated database connect api
- update code to import requests from requests library as botocore.vendored is de-supported
- provide the code, requirements, and a readme file so customers can update and create a zip file for changes in the future easily