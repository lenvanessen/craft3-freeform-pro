# Solspace Freeform Changelog

## 2.0.0-beta.6 - 2018-02-02
### Added
- Added a 'Use Double Opt-in?' setting for MailChimp integrations.
- Added `onBeforeSubmit` and `onAfterSubmit` events.
- Added an optional `renderSingleInput` method to render single Checkbox fields' input without an additional hidden input.

### Changed
- Changed Mailing List fieldtype `renderInput` to now only output the input field (without a label).

### Fixed
- Fixed a bug where the chart on Submissions list page inside CP was sometimes not displaying new submissions based on timezone.
- Fixed a bug where permissions weren't allowing Admins to change status of submission(s).

## 2.0.0-beta.5 - 2018-01-31
### Fixed
- Fixed a bug where the Freeform 1.x to 2.x (Craft 2.x to 3.x) migration path could error in some cases.
- Fixed a bug where an error could be triggered from the cleanup of unfinalized files.

## 2.0.0-beta.4 - 2018-01-30
### Fixed
- Fixed a bug where Freeform would trigger permission related errors when trying to edit users or user groups.
- Fixed a bug where Freeform would not hide pages from navigation that a user did not have permission access to.
- Fixed various permission issues throughout Freeform.

## 2.0.0-beta.3 - 2018-01-29
### Added
- Added Freeform 1.x to 2.x (Craft 2.x to 3.x) migration path.

### Fixed
- Fixed a bug where Email Notification templates would not update correctly.
- Fixed a bug in Export Profiles view.
- Fixed a bug for sites with databases table prefixes.
- Fixed a bug for some sites with issues installing Freeform.

## 2.0.0-beta.2 - 2018-01-25
### Fixed
- Fixed a bug where Submissions list in control panel would not display any results.
- Fixed a bug where some users encountered install errors/issues.
- Fixed a bug where the Freeform Form element field type would display an error.
- Fixed a bug where the Save button in Composer was sometimes out of position.

## 2.0.0-beta.1 - 2018-01-24
### Added
- Added compatibility for Craft 3.x.
