# docker-doc

*First*
---

- hostname :
```hostname``` 
- menjalankan image / menjalankan container:
```docker run -it (image)``` dgn versi ``` docker run -it ubuntu:18.04 sh ```
- sleep exit :
```docker run -it ubuntu sleep 100```  (wait 100 kemudian exit)
- mendeteksi container yang jalan :
```docker ps```
- mendeteksi container yang pernah kita jalanin :
```docker ps -a```
- melihat semua image yg pernah di download : 
```docker images```
- stop container :
```docker container stop (CONTAINER ID)``` 
- menjalankan container by CONTAINER ID :
```docker container start (CONTAINER ID)```
- masuk ke cli CONTAINER :
```docker exec -it (CONTAINER ID) sh```
- hapus container : 
```docker rm (CONTAINER ID)```
- set environment variabel pada image : 
```docker run -it '-e' () ```


*Contoh pada postgres design port agar bisa diakses local*
---
```docker run --name some-postgres -p 5432:5432 -e POSTGRES_PASSWORD=mysecretpassword -d postgres```






