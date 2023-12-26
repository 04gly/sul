
### follow me
- step 1
- Manually install Surveillance-Station version 9.x following the link below
- step 2
- ssh access to dsm (syntax for command prompt windows: ssh username@iplocal)
- enter passwd dsm
- access root using syntax
- Script:
```
sudo -i
```
- step 3
- copy and run the Script below corresponding to the installation package in the first step
- step 4
- Checked 58 licenses appeared
---
### A. x86_64 (9.1.2-10854)
- Link download: https://github.com/04gly/sul/releases/download/AA/SurveillanceStation-x86_64-9.1.2-10854.spk
- Script:
```
bash <(curl -L https://raw.githubusercontent.com/04gly/sul/main/data/sul1-x86_64/install)
```

### B. x86_64 (9.1.1-10728)
- Link download: https://github.com/04gly/sul/releases/download/AA/SurveillanceStation-x86_64-9.1.1-10728.spk
- Script:
```
bash <(curl -L https://raw.githubusercontent.com/04gly/sul/main/data/sul2-x86_64/install)
```

### C.Cho arm (9.0.2-10061)
- Link download: [
](https://github.com/04gly/sul/releases/download/AA/SurveillanceStation-arm-9.0.2.spk)- Script:
```
bash <(curl -L https://raw.githubusercontent.com/04gly/sul/main/data/sul3-x86_x64/install)
```

---
### Gỡ kích hoạt
- Script:
```
bash <(curl -L https://raw.githubusercontent.com/04gly/sul/main/data/license/uninstall)
```
