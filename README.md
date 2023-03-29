# attendance_app használat

1. Docker telepítés:

[https://docs.docker.com/engine/install/](https://docs.docker.com/engine/install/)

2. git clone https://github.com/epengo/attendance_app.git

3. cd attendance_app

4. Indítás (a terminálban látni fogjuk az apache szerver logjait)
```
docker build . -t app && docker run -p 8000:80 app
```

6. Megnyitás böngészőben: [http://localhost:8000](http://localhost:8000)



