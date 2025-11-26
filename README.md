# 1. 오픈소스 소프트웨어
- 오픈소스 라이선스 종류 : GPL, Apache License, MIT, BSD, CC, MPL, AGPL
- 오픈소스 형태의 운영체제 : 리눅스(Ubuntu, RHEL, CentOS, Fedora)
- 개발 시 활용되는 관리 시스템 : Git/GitHub, Gitlab
# 2. 리눅스
> 아래 내용은 Ubuntu 기준으로 작성되었음
## 2.1. 명령어 종류
1. 파일 관리 : `ls`, `cd`, `mkdir`, `rmdir`, `touch`, `vi`, `cat`, `mv`, `rm`, `find`
2. 쉘 : `chsh`, `echo`, `export`, `alias`, `unalias`, `history`
3. 파일 액세스 관리 : `chmod`, `umask`, `chown`
4. 패키지 관리 :

| 기능 | apt 형식 | apt-get / apt-cache 형식 |
|:---:|:---:|:---:|
| 패키지 검색 | apt search | apt-cache search |
| 패키지 정보 검색 | apt show | apt-cache show |
| 패키지 정보 업데이트 | apt update | apt-get update |
| 패키지 업그레이드 | apt upgrade | apt-get upgrade |
| 패키지 설치 | apt install | apt-get install |
| 패키지 삭제 | apt autoremove | apt-get autoremove |
| 패키지 파일 다운로드 | apt download | apt-get download |
5. 아카이빙/압축 : `tar`, `gzip`, `gunzip`, `bzip2`, `bunzip2`
6. 프로세스 : `ps`, `pgrep`, `kill`, `sleep`, `jobs`, `fg`, `bg`
7. 시스템 사용자 관리
  - 사용자 : `useradd`, `usermod`, `userdel`, `passwd`, `su`
  - 그룹 : `groupadd`, `groupmod`, `groupdel`, `gpasswd`, `newgrp`
8. 파일 시스템 관리 : `fdisk`, `mkfs`, `dd`, `df`, `du`, `mount`, `umount`
9. 네트워크 관리 : `nmcli`, `ip`, `route`, `ping`, `traceroute`, `netstat`, `nmap`, `ufw
# 3. GitHub
## 3.1. GitHub 활용법
### 3.1.1. 로컬 레포지토리에서 작업
### 3.1.2. 원격 레포지토리의 변경사항 가져오기
### 3.1.3. 브랜치 및 로그 확인
