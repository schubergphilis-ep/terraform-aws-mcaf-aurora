# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [5.0.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v5.0.0...v5.0.1) (2026-07-07)


### 🐛 Fixes

* migrate MCAF module sources ([#2](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/issues/2)) ([35615d2](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/commit/35615d2917560e18399d408ed80c0dc7f406ec18))

## [5.0.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v4.4.1...v5.0.0) (2026-03-03)


### ⚠ BREAKING CHANGES

* Add region support ([#65](https://github.com/schubergphilis/terraform-aws-mcaf-aurora/pull/65))

### 🚀 Features

* Add region support ([#65](https://github.com/schubergphilis/terraform-aws-mcaf-aurora/pull/65)) ([2165689](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/commit/21656891cffc883d39ebd06413cedca4abc0501b))

## [4.4.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v4.4.0...v4.4.1) (2026-02-27)


### 🐛 Fixes

* removed duplicate required providers config ([#64](https://github.com/schubergphilis/terraform-aws-mcaf-aurora/pull/64)) ([5ccb4bb](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/commit/5ccb4bb2c9c7ab66f98f62b274a98e52dd7fb294))

## [4.4.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v4.3.1...v4.4.0) (2026-01-26)


### 🚀 Features

* updating to new mcaf-role ([#63](https://github.com/schubergphilis/terraform-aws-mcaf-aurora/pull/63)) ([54e125e](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/commit/54e125e72e8dc012959d851ea32a10ef167982b5))

## [4.3.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v4.3.0...v4.3.1) (2025-01-07)


### 🐛 Fixes

* Add Global Writer endpoint to the outputs ([#62](https://github.com/schubergphilis/terraform-aws-mcaf-aurora/pull/62)) ([c54f37f](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/commit/c54f37f625541648b5599ac00bbe369cb464e5cd))

## [4.3.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v4.2.2...v4.3.0) (2025-01-06)


### 🚀 Features

* Add Global Database support ([#61](https://github.com/schubergphilis/terraform-aws-mcaf-aurora/pull/61)) ([58eec9d](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/commit/58eec9d02dd35e069f540ef84622c3ed29388752))

## [4.2.2](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v4.2.1...v4.2.2) (2024-12-16)


### 🐛 Fixes

* Correct variable types ([#60](https://github.com/schubergphilis/terraform-aws-mcaf-aurora/pull/60)) ([376253e](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/commit/376253ead3b236cb552d5ab3ae08e4f485d5e1a9))

## [4.2.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v4.2.0...v4.2.1) (2024-12-13)


### 🐛 Fixes

* Fix auto pauze configuration ([#59](https://github.com/schubergphilis/terraform-aws-mcaf-aurora/pull/59)) ([3884ab8](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/commit/3884ab883bd5c68935258e214ee27640c5a572ec))

## [4.2.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v4.1.1...v4.2.0) (2024-12-13)


### 🚀 Features

* Implement seconds_until_auto_pause to Serverless V2 and make configurable ([#58](https://github.com/schubergphilis/terraform-aws-mcaf-aurora/pull/58)) ([55a8b16](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/commit/55a8b16c8247252c6db330136e7f00ef566bcb73))

## [4.1.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v4.1.0...v4.1.1) (2024-01-12)


### 🐛 Fixes

* restore version bump ([#56](https://github.com/schubergphilis/terraform-aws-mcaf-aurora/pull/56)) ([ed8be65](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/commit/ed8be656a0ebba76fbd3ba18a703241830321011))
* bug: Fix resetting tags on every run ([#55](https://github.com/schubergphilis/terraform-aws-mcaf-aurora/pull/55)) ([b96743a](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/commit/b96743ab44efa1aa22307d76418bb757218d0c3a))

## [4.1.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v4.0.0...v4.1.0) (2024-01-11)


### 🚀 Features

* Add PostgreSQL support ([#54](https://github.com/schubergphilis/terraform-aws-mcaf-aurora/pull/54)) ([63bc7af](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/commit/63bc7afa02509642247df4426c1c4527a836734c))

## [4.0.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v3.3.0...v4.0.0) (2023-10-18)


### 🚀 Features

* breaking: modify the way security group ingress rules are defined allowing for more flexibility ([#53](https://github.com/schubergphilis/terraform-aws-mcaf-aurora/pull/53)) ([6b554c6](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/commit/6b554c679a840a5aef29a284cdc28beba8e8146a))

### 🐛 Fixes

* breaking: modify the way security group ingress rules are defined allowing for more flexibility ([#53](https://github.com/schubergphilis/terraform-aws-mcaf-aurora/pull/53)) ([6b554c6](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/commit/6b554c679a840a5aef29a284cdc28beba8e8146a))

## [3.3.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v3.2.1...v3.3.0) (2023-09-21)


### 🚀 Features

* security: solve latest checkov findings, modify behaviour of performance_insights and cloudwatch_logs_export ([#52](https://github.com/schubergphilis/terraform-aws-mcaf-aurora/pull/52)) ([cb7a15f](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/commit/cb7a15f511bc8b047d2c3e34ea2c279866f040fc))
* add the option to specify a custom parameter group name ([#50](https://github.com/schubergphilis/terraform-aws-mcaf-aurora/pull/50)) ([02fda64](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/commit/02fda640b139d5e22e1ad12c92d0e11097734461))

### 🐛 Fixes

* security: solve latest checkov findings, modify behaviour of performance_insights and cloudwatch_logs_export ([#52](https://github.com/schubergphilis/terraform-aws-mcaf-aurora/pull/52)) ([cb7a15f](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/commit/cb7a15f511bc8b047d2c3e34ea2c279866f040fc))
* bug: do not create cluster parameter group if no cluster parameters are specified ([#51](https://github.com/schubergphilis/terraform-aws-mcaf-aurora/pull/51)) ([718040d](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/commit/718040dc292c005c55f568c92f513a2a6ff7f7ff))

## [3.2.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v3.2.0...v3.2.1) (2023-09-18)


### 🐛 Fixes

* bug: solve dependency isues with modifying parameter groups ([#49](https://github.com/schubergphilis/terraform-aws-mcaf-aurora/pull/49)) ([a8361ed](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/commit/a8361ed91adc6123925d3a6c00b77ddbe6224c39))

## [3.2.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v3.1.1...v3.2.0) (2023-07-18)


### 🚀 Features

* Adds custom_endpoints output ([#44](https://github.com/schubergphilis/terraform-aws-mcaf-aurora/pull/44)) ([15f9abd](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/commit/15f9abdd06dcc768bf5e6b488d17d39d4f9addb7))

### 🐛 Fixes

* bug(entrypoint): Depend on cluster instances to exist ([#43](https://github.com/schubergphilis/terraform-aws-mcaf-aurora/pull/43)) ([e4d32b5](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/commit/e4d32b5ddcee82c21811bda860b45e562acca617))

## [3.1.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v3.1.0...v3.1.1) (2023-07-14)


### 🐛 Fixes

* bug:  `ca_cert_identifier` was only specified in the first cluster instance resource ([#48](https://github.com/schubergphilis/terraform-aws-mcaf-aurora/pull/48)) ([2ab7b93](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/commit/2ab7b936869385d24d093dbea027fab4e1cece6a))

## [3.1.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v3.0.0...v3.1.0) (2023-07-14)


### 🚀 Features

* security: set cluster parameter `require_secure_transport` to ON by default and set apply methods ([#47](https://github.com/schubergphilis/terraform-aws-mcaf-aurora/pull/47)) ([9723e57](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/commit/9723e57709a5ca2bfb321ace25d9384ebe0784ab))

## [3.0.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v2.0.1...v3.0.0) (2023-07-14)


### 🚀 Features

* Add support for creating multi-az db cluster and setting a custom ca cert identifer ([#45](https://github.com/schubergphilis/terraform-aws-mcaf-aurora/pull/45)) ([bc24dc5](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/commit/bc24dc5a088597f0443438e158321d6da01dd76b))

## [2.0.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v2.0.0...v2.0.1) (2023-06-16)


### 🐛 Fixes

* bug: support the creation of multiple RDS cluster endpoints in a single account ([#42](https://github.com/schubergphilis/terraform-aws-mcaf-aurora/pull/42)) ([3f274fa](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/commit/3f274fae4e5b05fcee5606b1395ca6e1a0284538))

## [2.0.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v1.0.0...v2.0.0) (2023-04-18)


### 🚀 Features

* breaking: add support for RDS managed master password ([#41](https://github.com/schubergphilis/terraform-aws-mcaf-aurora/pull/41)) ([f17a676](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/commit/f17a676b3d382f2cb51bdcfa778bfbcfcba29e22))

## [1.0.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v0.6.0...v1.0.0) (2023-03-30)


### 🚀 Features

* breaking: add support for: specifying endpoints and instance settings | rename variables | improve default settings ([#37](https://github.com/schubergphilis/terraform-aws-mcaf-aurora/pull/37)) ([2ed446a](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/commit/2ed446aa1b4c377b4d9a855793fd120517790444))

## [0.6.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v0.5.3...v0.6.0) (2023-03-21)


### 🚀 Features

* enhancement: update workflows, add examples, solve tflint/checkov findings ([#35](https://github.com/schubergphilis/terraform-aws-mcaf-aurora/pull/35)) ([2533498](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/commit/2533498d8ae7ee6a34f5e9525b6960d55574841f))

## [0.5.3](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v0.5.2...v0.5.3) (2023-03-20)


### 🚀 Features

* improvement: Calculate skip_final_snapshot ([#34](https://github.com/schubergphilis/terraform-aws-mcaf-aurora/pull/34)) ([1e5a792](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/commit/1e5a792bee9011884a55e08e08f5f6d96459c582))

## [0.5.2](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v0.5.1...v0.5.2) (2022-12-15)

## [0.5.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v0.5.0...v0.5.1) (2022-11-28)

## [0.5.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v0.4.9...v0.5.0) (2022-10-27)

## [0.4.9](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v0.4.8...v0.4.9) (2022-08-15)

## [0.4.8](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v0.4.7...v0.4.8) (2022-07-26)

## [0.4.7](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v0.4.6...v0.4.7) (2022-03-31)

## [0.4.6](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v0.4.5...v0.4.6) (2022-01-04)

## [0.4.5](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v0.4.4...v0.4.5) (2021-11-17)

## [0.4.4](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v0.4.3...v0.4.4) (2021-09-21)

## [0.4.3](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v0.4.2...v0.4.3) (2021-08-30)

## [0.4.2](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v0.4.1...v0.4.2) (2021-08-09)

## [0.4.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v0.4.0...v0.4.1) (2021-02-23)

## [0.4.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v0.3.1...v0.4.0) (2021-02-12)

## [0.3.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v0.3.0...v0.3.1) (2021-01-05)

## [0.3.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v0.2.0...v0.3.0) (2020-12-03)

## [0.2.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v0.1.11...v0.2.0) (2020-10-27)

## [0.1.11](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v0.1.10...v0.1.11) (2020-09-10)

## [0.1.10](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v0.1.9...v0.1.10) (2020-08-27)

## [0.1.9](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v0.1.8...v0.1.9) (2020-08-20)

## [0.1.8](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v0.1.7...v0.1.8) (2020-07-20)

## [0.1.7](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v0.1.6...v0.1.7) (2020-05-06)

## [0.1.6](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v0.1.5...v0.1.6) (2019-11-13)

## [0.1.5](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v0.1.3...v0.1.5) (2019-09-24)

## [0.1.3](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v0.1.4...v0.1.3) (2019-08-27)

## [0.1.4](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v0.1.2...v0.1.4) (2019-08-27)

## [0.1.2](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v0.1.1...v0.1.2) (2019-08-26)

## [0.1.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-aurora/compare/v0.1.0...v0.1.1) (2019-08-14)

## 0.1.0 (2019-08-09)
