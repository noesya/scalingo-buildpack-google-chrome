# Change Log
All notable changes to this project will be documented in this file.

## Scalingo buildpack

### 2026-06-21

- Added support for Scalingo-26.
- Dropped support for Scalingo-22.

### 2025-10-10
- Added support for Scalingo-24.
- Dropped support for Scalingo-18 and Scalingo-20.
- Scalingo-24 packages:
  - Removed `gconf-service`, `libappindicator1` & `libgconf-2-4`
  - Replaced `libasound2` with `libasound2t64`

### 2024-09-29
- Added `--disable-dev-shm-usage` flag to Chrome shims to prevent timeouts. ([source](https://github.com/GoogleChrome/lighthouse/issues/6512#issuecomment-1566851495))

### 2024-07-22
- Sync fork with Heroku's base repository, removing deprecation warning.

### 2022-09-13
- Changed stack check from Heroku-X to Scalingo-x.

## Heroku original buildpack

### 2024-05-30
- Deprecates support in Heroku-22 and Heroku-20.
- Adds explicit error for Heroku-24

### 2022-05-19
- Added support for Heroku-22.

### 2022-03-30
- Fixed bug where arguments with spaces don't work.

### 2022-03-29
- Explicitly unset `LD_PRELOAD` env variable.

### 2022-01-04
- Removed support for Cedar-14 and Heroku-16.
