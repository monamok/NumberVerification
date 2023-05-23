# v0.2.0
### This is the second pre-release of the Number Verification API
CAMARA community agreed to temporarily enable Number Verification API in two different flavours:

1. Based on CAMARA standardization guidelines, that enables API service on a dedicated endpoint and follows CAMARA AuthN/AuthZ concept.
- API [definition](./code/API_definitions/CAMARA/number_verification.yaml)
- API [documentation](./code/API_definitions/CAMARA/NUMBER_VERIFICATION_API.md)

2. Based on GSMA Mobile Connect standardized family of Identity APIs, that delivers Verified MSISDN service. 
- API [definition](./code/API_definitions/MobileConnect/numberVerify.yaml)
- API [documentation](./code/API_definitions/MobileConnect/MC_VERIFIED_MSISDN.md)

### Please note:
- This is a pre-release version, and should be considered as a draft for further development
- There are bug fixes and breaking changes to be expected in later versions
- The release is suitable for test implementations, but it is not recommended for use in production environments
- MC version was not changed in this release

### Added
* Add uml diagram for MC version by @DT-DawidWroblewski in https://github.com/camaraproject/DeviceStatus/pull/21

### Changed
* Guidelines alignment for CAMARA version by @monamok in https://github.com/camaraproject/NumberVerification/pull/19
  - error structure remodeled and aligned to the guidelines
  - documentation updated

### Fixed


### Removed


## New Contributors


**Full Changelog**: https://github.com/camaraproject/NumberVerification/compare/v0.1.0...v0.2.0

# v0.1.0
### This is the first pre-release of the CAMARA Number Verification API
CAMARA community agreed to temporarily enable Number Verification API in two different flavours:

1. Based on CAMARA standardization guidelines, that enables API service on a dedicated endpoint and follows CAMARA AuthN/AuthZ concept.
- API [definition](./code/API_definitions/CAMARA/number_verification.yaml)
- API [documentation](./code/API_definitions/CAMARA/NUMBER_VERIFICATION_API.md)

2. Based on GSMA Mobile Connect standardized family of Identity APIs, that delivers Verified MSISDN service. 
- API [definition](./code/API_definitions/MobileConnect/numberVerify.yaml)
- API [documentation](./code/API_definitions/MobileConnect/MC_VERIFIED_MSISDN.md)

### Please note:
- This is a pre-release version, and should be considered as a draft for further development
- There are bug fixes and breaking changes to be expected in later versions
- The release is suitable for test implementations, but it is not recommended for use in production environments

### Added
* Initial contribution of API spec Mobile Connect Number Verify v0.1.0 by @DT-DawidWroblewski in https://github.com/camaraproject/NumberVerification/pull/2
* Initial contribution of API spec CAMARA Number Verification v0.1.0 by @monamok in https://github.com/camaraproject/NumberVerification/pull/3
* Add documentation by @monamok in https://github.com/camaraproject/NumberVerification/pull/6

### Changed
* This is the first pre-release

### Fixed
* This is the first pre-release

### Removed
* This is the first pre-release

## New Contributors
* @DT-DawidWroblewski made their first contribution in https://github.com/camaraproject/NumberVerification/pull/2
* @monamok made their first contribution in https://github.com/camaraproject/NumberVerification/pull/3


**Full Changelog**: https://github.com/camaraproject/NumberVerification/commits/v0.1.0