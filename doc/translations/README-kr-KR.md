# sqlmap

[![Build Status](https://api.travis-ci.org/sqlmapproject/sqlmap.svg?branch=master)](https://travis-ci.org/sqlmapproject/sqlmap) [![Python 2.6|2.7|3.x](https://img.shields.io/badge/python-2.6|2.7|3.x-yellow.svg)](https://www.python.org/) [![License](https://img.shields.io/badge/license-GPLv2-red.svg)](https://raw.githubusercontent.com/sqlmapproject/sqlmap/master/LICENSE) [![PyPI version](https://badge.fury.io/py/sqlmap.svg)](https://badge.fury.io/py/sqlmap) [![GitHub closed issues](https://img.shields.io/github/issues-closed-raw/sqlmapproject/sqlmap.svg?colorB=ff69b4)](https://github.com/sqlmapproject/sqlmap/issues?q=is%3Aissue+is%3Aclosed) [![Twitter](https://img.shields.io/badge/twitter-@sqlmap-blue.svg)](https://twitter.com/sqlmap)

sqlmap은 오픈소스로 SQL Injection 취약점을 탐지, 공격하여 데이터 서버를 점령할 수 있는 침투 테스트 자동화 도구입니다.
해당 도구는 최고의 모의 테스터를 위한 강력한 탐지 엔진과 많은 편리 기능들, 데이터베이스 식별을 통한 광범위한 스위치들, 데이터베이스에 값을 가져오는 기능, 아웃오브밴드 통신을 통한 파일 시스템 접근과 운영체제 상의 명령어 실행 등에 기능이 있습니다.

**sqlmap 프로젝트는 [Netsparker Web Application Security Scanner](https://www.netsparker.com/scan-website-security-issues/?utm_source=sqlmap.org&utm_medium=banner&utm_campaign=github)에서 후원을 받고 있습니다.**

스크린샷
----

![스크린샷](https://raw.github.com/wiki/sqlmapproject/sqlmap/images/sqlmap_screenshot.png)

위키 [스크린샷 모음](https://github.com/sqlmapproject/sqlmap/wiki/Screenshots)에 들어가면 다양한 기능들을 볼 수 있습니다.

설치
----

[여기](https://github.com/sqlmapproject/sqlmap/tarball/master)를 클릭하여 최신버전의 tarball이나 [여기](https://github.com/sqlmapproject/sqlmap/zipball/master)를 클릭하여 최신버전의 zipball을 다운로드할 수 있습니다.

[Git](https://github.com/sqlmapproject/sqlmap) 저장소를 복제하여 sqlmap을 다운로드할 수 있습니다. :

    git clone --depth 1 https://github.com/sqlmapproject/sqlmap.git sqlmap-dev

sqlmap은 [파이썬](http://www.python.org/download/) 버전 **2.6**, **2.7**과 **3.x**이 설치된 모든 플랫폼에서 사용 가능합니다.

사용방법
----

기본 옵션과 스위치 옵션들 목록으로 보기:

    python sqlmap.py -h

모든 옵션과 스위치 사용법 목록으로 보기:

    python sqlmap.py -hh

[여기](https://asciinema.org/a/46601)서 샘플 실행을 찾을 수 있습니다.
sqlmap의 기능들, 지원하는 기능 항목과 모든 옵션, 스위치에 대한 설명과 예제를 보려면 [유저 매뉴얼](https://github.com/sqlmapproject/sqlmap/wiki/Usage)을 통해서 조언을 얻을 수 있습니다.

링크
----

* 홈페이지: http://sqlmap.org
* 다운로드: [.tar.gz](https://github.com/sqlmapproject/sqlmap/tarball/master) or [.zip](https://github.com/sqlmapproject/sqlmap/zipball/master)
* Commits RSS feed: https://github.com/sqlmapproject/sqlmap/commits/master.atom
* 이슈 트래커: https://github.com/sqlmapproject/sqlmap/issues
* 유저 매뉴얼: https://github.com/sqlmapproject/sqlmap/wiki
* 자주 묻는 질문 (FAQ): https://github.com/sqlmapproject/sqlmap/wiki/FAQ
* 트위터: [@sqlmap](https://twitter.com/sqlmap)
* 데모: [http://www.youtube.com/user/inquisb/videos](http://www.youtube.com/user/inquisb/videos)
* 스크린샷: https://github.com/sqlmapproject/sqlmap/wiki/Screenshots
