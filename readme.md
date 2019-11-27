# Express-generator 시작
~~~bash
#처음 실행하기 위해서는 아래의 명령을 한번만 실행한다.
npm i -g express-generator
#프로젝트를 처음 만들때
express --viwe=pug
npm i
~~~

# 터미널 창을 열고 package.json 파일을 열어서 "script" 항목에 아래의 내용을 추가한다.
~~~bash
"scripts": {
    "serve" : "supervisor ./bin/www",
    "start": "node ./bin/www"
}
~~~

# 터미널 창을 열고 supervisor를 아래와 같이 실행 시킨다.
~~~bash
npm run serve
~~~