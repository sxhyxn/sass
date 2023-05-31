MEMO만이 살 길
# sass 요즘엔 사용 안함, SCSS를 사용한다. (샤스싸쓰쌰쓰)
![image](https://github.com/sxhyxn/sass/assets/129706893/347deb2c-f247-46e7-815a-87aa6048d50e)

# scss 컴파일
![image](https://github.com/sxhyxn/sass/assets/129706893/0d1addab-6e08-4ee5-883b-5fd165fe394e)

# css 위치변경
![image](https://github.com/sxhyxn/sass/assets/129706893/605115c4-02c1-4ca9-b9a9-6131ebc9de93)

# savePath :null 이면 scss파일과 같은 위치에 style.css가 생긴다
![image](https://github.com/sxhyxn/sass/assets/129706893/c4adf7ea-c329-4fa0-9c25-4ae755d49de4)

# ~은 style.scss를 의미, /는 style.scss가 있는 폴더
![image](https://github.com/sxhyxn/sass/assets/129706893/f8aedaa1-77f1-41b2-9a89-70c8ee962d9d)

# scss 파일이 있는 폴더의 상위폴더에 생성
![image](https://github.com/sxhyxn/sass/assets/129706893/6adf5f1a-e786-4fea-8974-2e097e28d76e)

# 주석처리방법-----------
# // 주석처리방법은 css로 컴파일되지않는다
# /**/ 주석처리방법은 css로 컴파일 되어 나타난다
![image](https://github.com/sxhyxn/sass/assets/129706893/4b27d5c7-e926-44ba-8a56-37734abb01c1)

# 변수 만들기 --> $로 시작(영문,숫자, - , _ )만 사용할 수 있음, 숫자로 시작 불가능
![image](https://github.com/sxhyxn/sass/assets/129706893/f3d882f3-2356-4693-a448-140ee85eea93)

![image](https://github.com/sxhyxn/sass/assets/129706893/724b920c-afdf-4569-965d-ac6052780f52)

# Partials(파샬)
 -- 관련된것끼리 묶어서 분리 / 소스에 반복되는 부분들을 분리 분산시켜서 모듈화시키는 기능
 
  * Partials(파샬)의 파일명은 _ 로 시작하며
  * 불러들일때는 @import '파일명', 이 때 파일명에 _ 는 포함시키지 않고 확장명도 포함시키지 않는다.

SCSS는 _ 로 시작하는 파일은 컴파일하지 않는다.

![image](https://github.com/sxhyxn/sass/assets/129706893/34203867-43cb-41aa-856a-26f4a3085dcb)

# @import --> 변수가 중복될 때는 아래의 것이 적용

![image](https://github.com/sxhyxn/sass/assets/129706893/34a6a514-f94c-4954-a022-a248cc9a033c)

# @use --> 변수 이름이 같을 때 에러발생, @use를 사용할 때는 앞에 파일명을 추가해서 파일명.변수명 해주기
![image](https://github.com/sxhyxn/sass/assets/129706893/faf4d3a0-5b8a-48c1-884b-1d320ae9d119)
![image](https://github.com/sxhyxn/sass/assets/129706893/b8e09807-ffd5-4e30-8b75-3f4c7a23e242)

# as 뒤에 별명을 붙여서 사용 가능
![image](https://github.com/sxhyxn/sass/assets/129706893/cf6d33fe-1b46-4ded-a4ff-496692fd0752)



