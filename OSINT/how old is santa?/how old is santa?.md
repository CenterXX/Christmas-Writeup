# how old is santa?
- Category : OSINT
- Author : Center

<hr>

# Write up

how old is santa? 문제에 관한 설명이다

```
우연히 산타의 사진을 주웠어요!!

산타가 사진에 찍혔던 년도에 산타는 몇 살이었을까요???

공백은 _로 표시해주세요

플래그형식 Christmas{산타의 이름_나이}

3.jpg
```

다운 받은 사진이다

<img width="500" src="https://user-images.githubusercontent.com/90122834/146723252-50f87886-e150-4d1d-9de8-1d23cb0c97b9.JPG">

구글에서 지원하는 이미지 찾기 기능을 통해 간단하게 똑같은 사진이 보이는 사이트를 찾을 수 있었다

```https://www.pennlive.com/entertainment/2015/11/17_famous_people_you_wouldnt_e.html```

사이트 내에서 사진속 인물의 이름을 알수 있었다
- George Steinbrenner
- 사진에 찍혔던 년도는 1991년 인 것을 알았고 태어난 년도는 1930년 인것을 검색을 통해 알아냈다

Flag:```Christmas{George_Steinbrenner_61}```
