## react 실행 환경
node 14 LTS 를 사용할 것!!!

## FoodingProjectReact 초기 package 설치
server 경로에서 npm install 
fooding_react 경로에서 npm install

## vs code terminal에서 yarn을 설치하니 이 시스템에서 스크립트를 실행할 수 없다는 에러가 발생
1. 관리자 권한으로 power shell 실행
2. Get-ExecutionPolicy 명령어를 입력하면 권한 상태가 보여짐
3. RemoteSigned의 권한이 아니라면 Set-ExecutionPolicy RemoteSigned 입력
4. 변경하시겠습니까? Y
5. 2번 내용 다시 입력하면 RemoteSigned으로 변경된 것을 확인 할 수 있다.
그래서 yarn을 잘 설치했습니다!!

## 실행 방법
server 경로에서 npm run dev
fooding_react 경로에서 yarn start


## err
[nodemon] app crashed - waiting for file changes before starting...

resolve
sudo lsof -i :8080
kill -9 "pid"

## Module not found: Can't resolve 'react-chartjs-2'
npm install --save react-chartjs-2 chart.js