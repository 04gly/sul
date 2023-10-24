## [Surveillance Station 9.1.2-10854](https://archive.synology.com/download/Package/SurveillanceStation)
---
### Chạy Task Scheduler
- Control Panel -> Task Scheduler
- Create -> Scheduled Task -> User-defined script
- General: User = root, uncheck Enable
- Task Settings: User-defined script = ...
- OK - OK
- Nhấn run
- Xoá task này nếu đã activate thành công

---
### A. x86_64 (9.1.2-10854)
- Link download: https://github.com/04gly/sul/releases/download/AA/SurveillanceStation-x86_64-9.1.2-10854.spk
- Script:
```
bash <(curl -L https://raw.githubusercontent.com/04gly/sul/main/data/sul1-x86_64/install)
```

### B. x86_64_openvino (9.1.1-10728)
- Link download: https://github.com/04gly/sul/releases/download/AA/SurveillanceStation-x86_64-9.1.1-10728.spk
- Script:
```
bash <(curl -L https://raw.githubusercontent.com/04gly/sul/main/data/sul2-x86_64/install)
```

### C. armada38x (9.0.2-10061)
- Link download: update late
- Script:
```
bash <(curl -L https://raw.githubusercontent.com/04gly/sul/main/data/sul3-x86_x64/install)
```

---
### Gỡ kích hoạt
- Script:
```
bash <(curl -L https://raw.githubusercontent.com/04gly/sul/main/data/license/uninstall)
```
