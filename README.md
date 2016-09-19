# myKikiChat

[백엔드 특강 자료 참고](https://github.com/ulgoon/Node-to-gulp/blob/master/Understanding-of-backend(day2).md)


### git과 heroku 연동하기

* Heroku 연결
```
$ heroku app:create { nickname }heroku
$ heroku apps
```
```
$ heroku app:delete { nickname }heroku
$ git init
$ git add .
$ git commit -m "initial commit"
$ heroku git:remote -a { nickname }heroku
$ git push heroku master
```
```
$ heroku ps:scale web=1
$ heroku open
{ nickname }.herokuapp.com 접속
```


[헤로쿠 깃헙사용](http://unikys.tistory.com/317)

