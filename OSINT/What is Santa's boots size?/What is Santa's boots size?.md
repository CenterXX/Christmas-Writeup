# What is Santa's boots size?
- Category : OSINT
- Author : Center

<hr>

# Write up

What is Santa's boots size? 문제에 관한 설명이다

```
산타가 신발을 주문하려고 하는데 사이즈 기억이 안난대요!!

신발의 이름과 사이즈를 찾아주세요

사이즈는 밑에서 3번째꺼를 전부 적어주세요.

(공백은 _로 표시해주세요)

플래그 형식 Christmas{신발이름_사이즈값}

4.jpg
```

다운 받은 사진이다

<img width="500" src="https://user-images.githubusercontent.com/90122834/146724365-44d214b8-72a4-4d09-862c-d17f6a8a1d25.JPG">

구글에서 지원하는 이미지 찾기 기능을 통해  똑같은 사진이 보이는 사이트를 찾을 수 있었다

```https://www.jamesistore.com/index.php?route=product/category&cid=165&cname=wide+calf+santa+boots```

사이트 내에서 사진속 부츠의 이름을 알수 있었고 옆에 사이즈를 볼수 있는 버튼이 있었다

밑에서 3번쨰 사이즈들을 전부 적었다

```
US	EU	UK	CM
5	37.5	4.5	23
5.5	38	5	23.5
6	38.5	5.5	24
6.5	39	6	24.5
7	40	6	25
7.5	40.5	6.5	25.5
8	41	7	26
8.5	42	7.5	26.5
9	42.5	8	27
9.5	43	8.5	27.5
10	44	9	28
10.5	44.5	9.5	28.5
11	45	10	29
11.5	45.5	10.5	29.5
12	46	11	30
13	47.5	12	30.5
14	48.5	13	31
15	49.5	14	31.5
16	50.5	15	32
17	51.5	16	32.5
18	52.5	17	33
```


Flag:```Christmas{Wide_Top_Santa_Claus_Boot_1650.51532}```
