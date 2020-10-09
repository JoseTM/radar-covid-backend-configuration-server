# Changelog

All notable changes to this project will be documented in this file. 

## [Unreleased]

## [1.0.1.RELEASE] - 2020-10-09

### Added

- Country endpoint, which returns a list of countries of interest.
- Configured AWS Parameters Store for service property management.
- Management of aliases for access to different environments in Contentful.
- Cache time properties in masters data and texts endpoints.
- Added new records in GENERAL_CONFIGURATION table to store the Contentful aliases.
- Added CODE_OF_CONDUCT.md file.
- Added CHANGELOG.md file.

### Changed

- Modified exception handling. Error messages has been included.

### Deleted

- The properties files for Preproduction and Production environments have been removed, because these properties are stored encrypted in the infrastructure (AWS parameter stores).
- Deleted Headers started with "x-forwarded", in server logs.
- Deleted api-docs.yaml file. Yaml available through swagger endpoint.

### Fixed

- Fixed contact email in THIRD-PARTY-NOTICES file

## [1.0.0.RELEASE] - 2020-09-15

* Configuration Service. Initial version.

### Added

- Token UUID service, through which a unique identifier token is obtained.
- Settings service, through which the exposure configuration and other adjustment parameters are obtained.
- Locales service, which returns the list of available locales.
- Autonomous Community service, which returns the list of available autonomous communities.
- Texts service, through which internationalized texts are obtained.

[Unreleased]: https://github.com/RadarCOVID/radar-covid-backend-configuration-server/compare/1.0.1.RELEASE...develop
[1.0.1.RELEASE]: https://github.com/RadarCOVID/radar-covid-backend-configuration-server/compare/1.0.0.RELEASE...1.0.1.RELEASE
[1.0.0.RELEASE]: https://github.com/RadarCOVID/radar-covid-backend-configuration-server/releases/tag/1.0.0.RELEASE