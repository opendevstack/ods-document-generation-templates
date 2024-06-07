# Changelog

## Unreleased

## 1.2.8 - 2024-06-06
- RA doc in section 4.1 has got a typo in Description of column Requirement ([#142](https://github.com/opendevstack/ods-document-generation-templates/pull/142))
- Changed the branch name to N/A in the TIP for not included component ([#141](https://github.com/opendevstack/ods-document-generation-templates/pull/141))
- Added some clarification to TIP and TIR ([#140](https://github.com/opendevstack/ods-document-generation-templates/pull/140))
- Included the new "Requirements" column and the new description which include all the data that is going to be shown. ([#139](https://github.com/opendevstack/ods-document-generation-templates/pull/139))
- Included the complete Requirement description to Risk Assessment Table ([#138](https://github.com/opendevstack/ods-document-generation-templates/pull/138))
- Add support for partial deployment ([#137](https://github.com/opendevstack/ods-document-generation-templates/pull/137))

## 1.2.7 - 2023-11-20
- minor non-GxP handling fixes  ([#133](https://github.com/opendevstack/ods-document-generation-templates/pull/133))
- Align center for first column in table in CSD ([#125](https://github.com/opendevstack/ods-document-generation-templates/issues/125))
## 1.2.6 - 2023-11-07
- Rework non gxp messages ([#126](https://github.com/opendevstack/ods-document-generation-templates/issues/126))
- Bugfix/cftr document presents an inconsistent behaviour between testing sections ([#124](https://github.com/opendevstack/ods-document-generation-templates/pull/124))
- Remove overlapping headers for tables spanning multiple pages ([#121](https://github.com/opendevstack/ods-document-generation-templates/pull/121))
- Remove CFTR reference from TRC document ([#115](https://github.com/opendevstack/ods-document-generation-templates/pull/115))
- RA: GxP Relevance section available for GxP projects only ([#118](https://github.com/opendevstack/ods-document-generation-templates/issues/118))
- IVP, IVR: Redundant bullets in ch12 ([#119](https://github.com/opendevstack/ods-document-generation-templates/issues/119))
- TRC: Content wrappable in section 4 table ([#128](https://github.com/opendevstack/ods-document-generation-templates/issues/128))

## 1.2.5 - 2023-10-02
- Add global font-size config in CSS ([#114](https://github.com/opendevstack/ods-document-generation-templates/pull/114))

## 1.2.4 - 2023-07-03
- Use a consistent notion of document version ([#95](https://github.com/opendevstack/ods-document-generation-templates/issues/95))
- CFTP templates adjusted to support non-GxP projects ([#100](https://github.com/opendevstack/ods-document-generation-templates/issues/100))
- Improve Document Generation Experience ([#97](https://github.com/opendevstack/ods-document-generation-templates/issues/97))
- Update Reference Documents & Base Documents sections ([#101](https://github.com/opendevstack/ods-document-generation-templates/issues/101))
- Fix SSDS appendix per gamp and RA chapter 5 ([#103](https://github.com/opendevstack/ods-document-generation-templates/issues/103))
- CSD document could display an overlapping between JIRA issue and table ([#106](https://github.com/opendevstack/ods-document-generation-templates/issues/106))
- HTML is not interpreted in IVR document ([#109](https://github.com/opendevstack/ods-document-generation-templates/issues/109))

## 1.2.3 - 2022-11-17
- Disallow ConfigSpecs in CSD for GAMP 3 ([#93](https://github.com/opendevstack/ods-document-generation-templates/pull/93))
- Enable all GAMP Categories in the CSD documents for GAMP3/4/5 ([#91](https://github.com/opendevstack/ods-document-generation-templates/pull/91))
- Add check for project property PROJECT.IS_GXP in SSDS templates ([#90](https://github.com/opendevstack/ods-document-generation-templates/pull/90))
- Rename BuildConfig and DeploymentConfig to abstract *Resource ([#88](https://github.com/opendevstack/ods-document-generation-templates/pull/88))

## 1.2.2 - 2022-11-18

## 1.2 - 2022-10-04
### Added
- Allow Discrepancies in EDP Templates([#84](https://github.com/opendevstack/ods-document-generation-templates/pull/84))
- Fix CI name of Container PAAS system references([#85](https://github.com/opendevstack/ods-document-generation-templates/pull/85))
- Fix truncated table in SSDS when emails cannot be truncated ([#86](https://github.com/opendevstack/ods-document-generation-templates/pull/86))
- Allow re-deployments and advancing to P despite defects ([#87](https://github.com/opendevstack/ods-document-generation-templates/pull/87))

## 1.2 - 2022-02-18
### Added
- CFTP for Gamp3/4/5 - Purpose chapter 7.1.1 needs changes([#64](https://github.com/opendevstack/ods-document-generation-templates/pull/64))
- SDSS for GAMP3/4 - Missing Section 3.2.x tokens for replacement ([#67](https://github.com/opendevstack/ods-document-generation-templates/issues/67))
- CFTP for GAMP3/4/5 improvements ([#73](https://github.com/opendevstack/ods-document-generation-templates/pull/73))
- Add missing chapter numbers([#77](https://github.com/opendevstack/ods-document-generation-templates/pull/77))
- Fixes column widths in various document templates([#80](https://github.com/opendevstack/ods-document-generation-templates/pull/80))
- Fix table column wrappings([#82](https://github.com/opendevstack/ods-document-generation-templates/pull/82))

## 1.2 - 2021-18-11

### Added
- Fix some wording the the RA document, and adjust a table in the chapter 4.2.1 ([#49](https://github.com/opendevstack/ods-document-generation-templates/pull/49))
- Modified SSDS document to use Pull Request info not SonarQube ([#614](https://github.com/opendevstack/ods-jenkins-shared-library/pull/614))
- Add missing table in RA document ([#50](https://github.com/opendevstack/ods-document-generation-templates/pull/50))
- Add missing column in section 4 of TRC document ([#51](https://github.com/opendevstack/ods-document-generation-templates/pull/51))
- Remove table and add comment in the section 7 (conclusions) of the IVP document ([#52](https://github.com/opendevstack/ods-document-generation-templates/pull/52))
- TIR and DTR documents are not properly indexed ([#47](https://github.com/opendevstack/ods-document-generation-templates/pull/47))
- Improve description for SSDS Source Code Review table ([#54](https://github.com/opendevstack/ods-document-generation-templates/pull/54))
- Updated section 12 in SSDS-5 to remove SonarQube references ([#55](https://github.com/opendevstack/ods-document-generation-templates/pull/55))
- Add support for ods-saas-service component type ([#31](https://github.com/opendevstack/ods-document-generation-templates/pull/31))
- Fix failure in CSD for GAMP 5 ([#57](https://github.com/opendevstack/ods-document-generation-templates/pull/57))
- Improve naming of xUnit attachment section to name inclusion of test evidence ([#58](https://github.com/opendevstack/ods-document-generation-templates/pull/58))
- Fix whitespace behavior in Development Testing Results table ([#60](https://github.com/opendevstack/ods-document-generation-templates/pull/60))

### Fixed - 2021-04-22
- Fix the document history section for IVR still shows the wrong title ([#44](https://github.com/opendevstack/ods-document-generation-templates/pull/44))
- Remove .idea directory ([#45](https://github.com/opendevstack/ods-document-generation-templates/pull/45))

### Fixed - 2021-04-15
- Bugfix/big table content overflow ([#32](https://github.com/opendevstack/ods-document-generation-templates/pull/32))
- IVP and IVR Document History Section is not Correct ([#34](https://github.com/opendevstack/ods-document-generation-templates/pull/34))
- Remove border from wrapper table ([#38](https://github.com/opendevstack/ods-document-generation-templates/pull/38))
- Fix table overflow within IVP and IVR docs ([#40](https://github.com/opendevstack/ods-document-generation-templates/pull/40))

## 1.1

### Fixed - 2021-10-01
- Fix RA table overflow replacing unicode character in jira keys ([#56](https://github.com/opendevstack/ods-document-generation-templates/pull/56))

