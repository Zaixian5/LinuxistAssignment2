# 1-3 문제 소스코드
<h4>사용법</h4>
1) pangCmd.lua 스크립트 파일을 redis 작업을 진행할 디렉토리로 이동시킵니다.
2) redis-server를 실행후 다른 터미널에서 아래 명령어를 입력합니다.
<li>redis-cli EVAL "$(cat pangCmd.lua)" 0 pang</li>
3) 터미널 창에 "PUNG"이라는 문자열이 출력됩니다.
