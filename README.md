# install-linuxdeployqt-action
A fast (entirely shell-based) and maintained GitHub Action for installing `linuxdeployqt` on x64/ARM64 Linux runners

# Usage
```
- name: Install linuxdeployqt
  uses: Fryy_55/install-linuxdeployqt-action@v1.0.0
```
Replace `v1.0.0` with the version you want to use

The installed binary will be on PATH and will be named `linuxdeployqt` _independently_ of the ISA of the runner

# License
This project is distributed under the **MIT License**.

See `LICENSE` for permissions, conditions and limitations.
