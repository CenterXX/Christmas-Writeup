# injured rudolph
- Category : WEB
- Author : Center

<hr>

# Write up

injured rudolph 문제에 관한 설명이다

```
하늘을 나는 썰매 타고 있는 와중 루돌프 발목이 삐끗하였다

루돌프의 다리를 치료할 방법을 찾아주자 !

https://christmas-web1.herokuapp.com/
```
간단한 ssti 문제이다 
- 관리자 도구를 열어 주석처리된 request값을 발견 할 수 있다 = santa
- reauset 값을 통해 /?santa={{config}} 를 입력시 플래그를 획득 할 수 있다

Flag:```Christmas{Rudolfu_G0_H0spital}```
