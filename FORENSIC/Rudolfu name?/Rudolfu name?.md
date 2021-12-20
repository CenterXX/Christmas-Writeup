# Rudolfu name?
- Category : FORENSIC
- Author : Center XX

<hr>

# Write up

Rudolfu name? 문제에 관한 설명이다

```
악당에게서 탈출한 산타 루돌프를 불러야 하는데

루돌프 이름을 까먹어버렸다!

루돌프의 이름을 찾아라 !

Rudolfu.jpg
```
Linux 를 사용하여 사진을 분석하기위해 Rudolfu 라는 폴더를 만들었다
- binwalk
- foremost

<img width="500" src="https://user-images.githubusercontent.com/90122834/146732148-a03a7712-4631-4af7-9cc7-5cf3ae8f8f02.png">

binwalk를 통해 zip 파일을 확인 foremost 를 사용하여 데이터 복구를 했다

```
center@kali:~/Desktop/Rudolfu/output$
center@kali:~/Desktop/Rudolfu/output$ ls
center@kali:~/Desktop/Rudolfu/output$
audit.txt jpg zip 
center@kali:~/Desktop/Rudolfu/output$cd zip
center@kali:~/Desktop/Rudolfu/output/zip$ ls
center@kali:~/Desktop/Rudolfu/output/zip$
00000228.zip
center@kali:~/Desktop/Rudolfu/output/zip$ unzip 00000228.zip
Archive:  00000228.zip
    creating: Rudolfu/
   inflating: Rudolfu/name.zip
   center@kali:~/Desktop/Rudolfu/output/zip$ ls
   center@kali:~/Desktop/Rudolfu/output/zip$
   00000228.zip Rudolfu
   center@kali:~/Desktop/Rudolfu/output/zip$ cd Rudolfu
   center@kali:~/Desktop/Rudolfu/output/zip/Rudolfu$ ls
   center@kali:~/Desktop/Rudolfu/output/zip/Rudolfu$
   name.zip
    center@kali:~/Desktop/Rudolfu/output/zip/Rudolfu$ unzip  name.zip
    Archive:  name.zip
    [name.zip] name.txt password:
    
    ```
   
   
    - 패스워드는 wikipedia 에서 획득할 수가 있다
    - 패스워드 입력시 cat 명령어를 사용하여 플래그를 획득할 수 있다
    

Flag:```Christmas{Chir0sla}```
