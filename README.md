# Arch package symlinks

The executables of some packages are located in directories that are not included in the `PATH` environment variable.
And then there are packages with very log executable file names.

These packages give concise name symbolic links to these executables.

## How to use

For example,

```bash
cd ./stoplight-studio-appimage-symlink

makemkg -sri
```
