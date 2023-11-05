[실습 설명] (https://happycloud-lee.tistory.com/52)

npm install --save express body-parser express fs ejs
--save옵션을 주어 package.json에 종속 라이브러리가 dependency항목 밑에 추가되도록 합니다.

### 테스트

- package.json을 열어, scripts.start구문에 'node index.js'를 추가합니다.

### github 연결
https://github.com/Git-Hello-77/hellnode.git
push할때마다 암호를 묻지 않게 하려면 아래 예와 같이 credential정보를 캐싱합니다. 아래예는 1시간 캐싱.

git config credential.helper 'cache --timeout=3600'