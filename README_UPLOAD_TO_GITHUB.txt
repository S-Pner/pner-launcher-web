이 폴더는 v14 원격 파일 설치 기능 테스트용 예시입니다.

GitHub Pages 저장소(pner-launcher-web)에 아래 폴더를 그대로 추가하면 됩니다.
- manifests/pner_test_12110.files.json
- files/test/v14-test.txt

그리고 GitHub의 servers.json에서 테스트 서버 항목에 아래 줄을 추가하면,
피너런처 v14가 서버 선택 시 이 파일목록을 읽고 설치 버튼을 눌렀을 때 v14-test.txt를 다운로드합니다.

"manifest": "manifests/pner_test_12110.files.json"

다운로드 위치:
%APPDATA%\PnerLauncher\games\pner_test_12110\pnerlauncher\v14-test.txt
