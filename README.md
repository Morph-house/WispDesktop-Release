# Wisp Desktop

카카오톡 봇 스크립트(Wisp 레거시 API)를 **PC에서 바로 테스트**할 수 있는 데스크톱 툴입니다.
카카오톡이나 안드로이드 기기 없이, 메시지를 입력해서 봇의 답장을 확인할 수 있습니다.

## 주요 기능

- 프로젝트 폴더(`project.json` 순서대로) 스크립트 실행
- 방마다 채팅창을 따로 열기, 카카오톡 같은 말풍선 UI
- 긴 봇 답장은 말줄임표(`…`)와 `전체보기`로 줄여서 보여주고, 누르면 전체 메시지 확인
- 방 추가, 이름 변경, 단체방 설정
- 프로젝트 폴더와 데이터 폴더 경로 기억

## 실행 방법

1. Java 17 이상이 필요합니다.
2. 배포 파일을 내려받아 압축을 풀고 실행 파일을 실행합니다.

## 주의

- 봇 스크립트는 포함되어 있지 않습니다. 사용자가 직접 가진 프로젝트 폴더를 불러와서 사용합니다.
- 데이터 폴더에는 봇이 쓰는 DB 파일(JSON)이 필요합니다.

## 사용한 오픈소스

- [Rhino](https://github.com/mozilla/rhino) (MPL 2.0)
- [FlatLaf](https://github.com/JFormDesigner/FlatLaf) (Apache 2.0)
- [JSON-java](https://github.com/stleary/JSON-java)
