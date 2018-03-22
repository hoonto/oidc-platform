## [v2.2.0](https://github.com/synapsestudios/oidc-platform/compare/v2.1.2...v2.2.0) - 2018-03-2
### Added
- [#254](https://github.com/synapsestudios/oidc-platform/pull/254) Add Redis port to common.env and documentation
- [#251](https://github.com/synapsestudios/oidc-platform/issues/251) Add ability to delete profile picture
- [#240](https://github.com/synapsestudios/oidc-platform/issues/240) Add self signed SSL certificates to dev environment
- [#227](https://github.com/synapsestudios/oidc-platform/pull/227) Add helpful logs and exits
### Changed
- [#178](https://github.com/synapsestudios/oidc-platform/issues/178) Remove user_password_reset_token table and associated models/methods
- [#249](https://github.com/synapsestudios/oidc-platform/issues/249) Update trap email handling
- [#248](https://github.com/synapsestudios/oidc-platform/pull/248) Change certs
- [#247](https://github.com/synapsestudios/oidc-platform/pull/247) Make hoursTilExpire configurable for email tokens
### Fixed
- [#260](https://github.com/synapsestudios/oidc-platform/issues/260) Fix Validation failing when registration form linked from login form submitted #260
- [#231](https://github.com/synapsestudios/oidc-platform/issues/231) Fix build scripts so docker-compose up always works #231
- [#255](https://github.com/synapsestudios/oidc-platform/issues/255) Fix broken migrations
- [#253](https://github.com/synapsestudios/oidc-platform/pull/253) Resend Verification button causing 500 errors

## [v2.1.2](https://github.com/synapsestudios/oidc-platform/compare/v2.1.1...v2.1.2) - 2017-12-1
### Changed
- [#235](https://github.com/synapsestudios/oidc-platform/issues/235) Fix profile photo upload
## [v2.1.1](https://github.com/synapsestudios/oidc-platform/compare/v2.1.0...v2.1.1) - 2017-11-22
### Changed
- [#230](https://github.com/synapsestudios/oidc-platform/issues/230) add login link to forgot password screen
## [v2.1.0](https://github.com/synapsestudios/oidc-platform/compare/v2.0.0...v2.1.0) - 2017-10-23
### Changed
- [#203](https://github.com/synapsestudios/oidc-platform/issues/203) Implement a system for webhooks
- [#200](https://github.com/synapsestudios/oidc-platform/issues/200) Allow templates to have "options" and use those options to set custom subjects for emails
- [#67](https://github.com/synapsestudios/oidc-platform/issues/67) Make user registration configurable
- [#137](https://github.com/synapsestudios/oidc-platform/issues/137) Stop hard coding the pairwise salt
- [#112](https://github.com/synapsestudios/oidc-platform/issues/112) Env var to control client initiated logout
- [#141](https://github.com/synapsestudios/oidc-platform/issues/141) Add user/client to templates
- [#142](https://github.com/synapsestudios/oidc-platform/issues/142) Remove deprecated template schema
- [#59](https://github.com/synapsestudios/oidc-platform/issues/59) Change password
- [#114](https://github.com/synapsestudios/oidc-platform/issues/114) Email Settings
## [v2.0.0](https://github.com/synapsestudios/oidc-platform/compare/v1.4.0...v2.0.0) - 2017-10-10
### Changed
- [#162](https://github.com/synapsestudios/oidc-platform/issues/162) Stop allowing the access token for auth on the profile screen
- [#138](https://github.com/synapsestudios/oidc-platform/issues/138) Stop hardcoding nonce when resetting passwords
- [#119](https://github.com/synapsestudios/oidc-platform/issues/119) Updated to to [node-oidc](https://github.com/panva/node-oidc-provider) v2.3.2
### Added
- [#115](https://github.com/synapsestudios/oidc-platform/issues/115) Theming. See [theming guide](docs/theming.md) for details
- [#131](https://github.com/synapsestudios/oidc-platform/issues/131) Password Grant now returns an id token as well as an access token

## [v1.4.0](https://github.com/synapsestudios/oidc-platform/compare/v1.3.1...v1.4.0) - 2017-10-3
### Added
- [#127](https://github.com/synapsestudios/oidc-platform/pull/127) Update mysql config to be closer to AWS RDS mysql

## [v1.3.1](https://github.com/synapsestudios/oidc-platform/compare/v1.3.0...v1.3.1) - 2017-10-2
### Added
- [#123](https://github.com/synapsestudios/oidc-platform/pull/123) Allow password grant type in database.