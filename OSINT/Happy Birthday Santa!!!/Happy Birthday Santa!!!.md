# Happy Birthday Santa!!!
- Category : OSINT
- Author : Center

<hr>

# Write up

Happy Birthday Santa!!! 문제에 관한 설명이다

```
산타 몰래 생일을 축하하기위해 케이크를 주문했어요!

케이크 가게에 가서 산타의 케이크를 가져와주세요!!

공백은_로 표시해주세요

플래그형식 Christmas{가게이름(생일)}

5.jpg
```

다운 받은 사진이다 윗 부분이 잘려있는 걸 확인할 수 있다

<img width="500" src="https://user-images.githubusercontent.com/90122834/146725553-3de2cc2b-68a6-4c52-a09d-d25eb6eed974.JPG">

구글에서 지원하는 이미지 찾기 기능을 통해서도 제공된 사진을 발견할 수 없었다

- 그래서 사진에 나와있는 HOHO를 사용해서 검색해봤다
- HOHO Cake 라고 검색한 결과 온전한 사진을 발견할 수 있었다
- 사진을 클릭해 가게이름이 Cake Craft Shop 인걸 확인 할수 있었다

```https://www.cakecraftshop.co.uk/shop/products/Cute-Santa-Ho-Ho-Ho-Pick-Cake-Topper.htm```

구글 검색을 통해 산타의 생일이 ```3월15인 것을 확인했다```

Flag:```Christmas{Cake_Craft_Shop(315)}```

