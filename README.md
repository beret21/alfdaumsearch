alfdaumsearch
=============

자동완성 가능한 Daum 키워드 검색과 Daum 사전(카카오 사전) 검색을 가능하도록 하는 Alfred Workflow

> 이 프로젝트는 [Kuniz/alfdaumsearch](https://github.com/Kuniz/alfdaumsearch) (v0.2.3)에서 2026-03-01에 포크하여 독립적으로 유지보수하고 있습니다.


변경 이력 (v0.3.0~)
------

- v0.3.1 (2026-03-01)
  - `dj` 키워드를 한일사전으로 변경
  - 개발자 정보를 Yoonseok Jang으로 변경
  - 설치방법 간소화 (macOS Tahoe 이상 Python 3 기본 포함)

- v0.3.0 (2026-03-01)
  - 사용하지 않는 사전 키워드 19개 제거 (5개만 유지)
  - `dk` 키워드를 국어사전에서 한영사전으로 변경
  - API 응답이 비어있을 때 발생하는 오류 수정
  - macOS Tahoe 26.4 동작 확인


설치방법
------

- [releases](../../releases/latest) 페이지의 `alfdaumsearch.alfredworkflow`를 다운로드 받아서 실행한다.
- Alfred 4.0 이상 필요
- Python 3 이상 필요 (macOS Tahoe 이상에서는 기본 포함)
- macOS Tahoe 26.4에서 테스트 및 동작 확인


사용법
----

 * `ds ...` : 일반 키워드 검색
 * `de ...` : 영한사전 검색
 * `dk ...` : 한영사전 검색
 * `dh ...` : 한자사전 검색
 * `dj ...` : 한일사전 검색


단축키

* Cmd + C : 상세 내용이 클립보드에 복사
* Cmd + N, C : 자동완성 텍스트가 클립보드로 복사
* Cmd + Y 혹은 Shift : 검색결과 미리 보기 웹브라우져 출력


외부 모듈 사용
-----------
[Alfred-workflow](https://github.com/deanishe/alfred-workflow) 모듈을 사용하였습니다.


LICENSE
-------
 - MIT
