# Dnslog-Docker

[![Docker Automated Build](https://img.shields.io/docker/automated/xrsec/dnslog?label=Build&logo=docker&style=flat-square)](https://hub.docker.com/r/xrsec/dnslog) [![Docker dnslog Build](https://github.com/XRSec/Dnslog-Docker/actions/workflows/Docker%20dnslog%20Build.yml/badge.svg)](https://github.com/XRSec/Dnslog-Docker/actions/workflows/Docker%20dnslog%20Build.yml)

> Docker Auto Restart
```bash
--restart=always
```

## [donot-wong/dnslog](https://github.com/donot-wong/dnslog) 

- weblog/dnslog平台 Docker容器化部署

```bash
docker run -it -d \
  -p 8080:8000 \
  -v ./dnslog:/usr/src/app/dnslog \
  xrsec/dnslog:donot-wong_dnslog
```


## [trysec/BlueLotus_XSSReceiver](https://github.com/trysec/BlueLotus_XSSReceiver)

- XSS平台 CTF工具 Web安全工具
- XSS数据接收平台（无SQL版）

```bash
docker run -it -d -p 8080:80 xrsec/dnslog:trysec_bluelotus_xssreceiver
```

> XRSec has the right to modify and interpret this article. If you want to reprint or disseminate this article, you must ensure the integrity of this article, including all contents such as copyright notice. Without the permission of the author, the content of this article shall not be modified or increased or decreased arbitrarily, and it shall not be used for commercial purposes in any way
