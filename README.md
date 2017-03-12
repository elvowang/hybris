# Hybris

## Ant based Hybris automations.

### Prequiresites

  - Java SDK Version >= v8
  - `ANT_HOME` defined in System environment variables (version >= 1.9.0).
  - `ANT_OPTS` defined in System environment variables (OPTIONAL), e.g. `-Xmx512m -Dfile.encoding=UTF-8`.
  - `HYB_BIN_DIR` defined and appointed to your local Hybris `bin` package by the following orders:
    * passed in by CLI.
    * defined in System environment variables.
    * defined in `.env` (ignored by `.gitignore`).

### Getting Started

  ```bash
  git clone https://github.com/jimzhan/hybris.git && cd hybris
  ant bootstrap
  ```

### Scaffoldings 

- `bootstrap` - synchronize the packages to create a new instance with multi settings profiles supports (develop/develop, testing/production).


### Why `Ant`?

- first class integreation with Hybris OOTB automations.
- stable and fast especially comparing to `Gradle`.
- simple and work~

**NOTE** Hybris OOTB ant tasks remain the same.


### TODOs
- [x] Hybris OOTB ant tasks integrations.
- [x] Multi settings profiles supports.
- [ ] daemon server supports.
- [ ] running server detections.