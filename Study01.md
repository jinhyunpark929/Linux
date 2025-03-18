## 📍Study01 - Commands to verify after installing Linux


```bash
user@user:~$ lsb_release -a
No LSB modules are available.
Distributor ID: Ubuntu
Description:    Ubuntu 24.04.2 LTS
Release:        24.04
Codename:       noble
```

'No LSB modules are available.' 발생 원인
-> Linux Standard Base (LSB) 모듈이 현재 시스템에 설치되어 있지 않음을 의미함, 24.04 noble 버전에서는 불필요함

해결 방안 : lsb_release -a 2>/dev/null 입력하면 해당 경고 메세지 없어짐

