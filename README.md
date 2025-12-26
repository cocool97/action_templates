# Github action templates

## Rust

### Reusable workflows

|   **Template name**   |                                      **Description**                                       |
| :-------------------: | :----------------------------------------------------------------------------------------: |
|   rust-quality.yml    |                          Run various quality checks over the code                          |
| rust-build-matrix.yml | Build the project on various platforms (_ubuntu-latest_, _windows-latest_, _macos-latest_) |

### Composite actions

| **Action name** |                     **Description**                     |
| :-------------: | :-----------------------------------------------------: |
|   rust-build    |         Build the project on various platforms          |
|   rust-clippy   |                Run clippy on the project                |
|    rust-doc     |           Build documentation for the project           |
|    rust-fmt     |              Run formatter on the codebase              |
|  rust-outdated  | Run `cargo-outdated` to check for outdated dependencies |
|   rust-setup    |              Setup rust build environment               |
|    rust-test    |                    Run project tests                    |
