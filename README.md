alfdaumsearch  ![Test](../../actions/workflows/test-daum-ac.yml/badge.svg) ![Release](../../actions/workflows/release.yml/badge.svg)
=============

 자동완성 가능한 Daum 키워드 검색과 Daum 사전(카카오 사전) 검색을 가능하도록 하는 Alfred Workflow


설치방법
------

- [releases](../../releases/latest) 페이지의 `alfdaumsearch.alfredworkflow`를 다운로드 받아서 실행한다.

- MacOS 12.3 이상의 경우
  - python3 설치
    - `brew install python`
    - `xcode-select --install`
- Alfred 4.0 이상 필요
- Python 3 이상 필요
- macOS Tahoe 26.4에서 테스트 및 동작 확인
 
사용법
----

 * `ds ...` : 일반 키워드 검색
 * `de ...` : 영한사전 검색
 * `dk ...` : 한영사전 검색
 * `dh ...` : 한자사전 검색
 * `dj ...` : 일어사전 검색


단축키 관련 기능 추가

* Cmd + C : 상세 내용이 클립보드에 복사
* Cmd + N, C : 자동완성 텍스트가 클립보드로 복사
* Cmd + Y 혹은 Shift : 검색결과 미리 보기 웹브라우져 출력

적용되어 있는 것 이외에 기능 추가를 원하시면 요청바랍니다.


외부 모듈 사용
-----------
Alfred-workflow(https://github.com/deanishe/alfred-workflow) 라는 모듈을 사용하였습니다.



LICENSE
-------
 - MIT
