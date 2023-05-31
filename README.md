# 🎀 sass 확장프로그램 설치
      거의 사용안함. scss를 사용한다. scss --> 사스(라고 읽음)
![image](https://github.com/hyejin192/sass/assets/129017064/0c9c7cb8-ce41-42e2-8031-3731c00571bc)

      확장프로그램 설치
![image](https://github.com/hyejin192/sass/assets/129017064/bed598ea-4ee1-4ec9-b247-fc33b665b5b8)

      터미널 누르고 하단 watch scss 클릭

![image](https://github.com/hyejin192/sass/assets/129017064/4f9a0520-04c4-45c1-a048-85091b029eb6)

       자동으로 style.css가 컴파일 됨 index 연결은 style.css

![image](https://github.com/hyejin192/sass/assets/129017064/2707ee28-6159-486f-a038-f293fd4946ca)

      css 위치 변경 네모칸 안을 클릭하면 밑 화면으로 이동

![image](https://github.com/hyejin192/sass/assets/129017064/b29a10f1-7a7a-4852-a220-aa295f64c96c)

      savaPath:null이면 scss 파일과 같은 위치에 style.css가 생긴다.

![image](https://github.com/hyejin192/sass/assets/129017064/68f83bc3-d03a-43fa-9a3e-6bd352dad30b)

      savaPath의 위치가 ~/css면 부모 폴더에 css폴더가 생김 (~은 style.scss를 의미, /는 style.scss가 있는 폴더를 의미)
      
![image](https://github.com/hyejin192/sass/assets/129017064/da04f562-ee4a-4ba9-80bc-266c4d71586b)

      ~/../css는 scss파일이 있는 폴더의 상위요소에 생성
      
#  🔎 주석처리방법
      
![image](https://github.com/hyejin192/sass/assets/129017064/0b02ff1e-9477-45c7-98ec-5c003696b0a8)

      //주석문 은 css로 컴파일되지 않는다.
      /* 주석문 */ : css로 컴파일된다.
      
# 🏝️ 변수만들기 

![image](https://github.com/hyejin192/sass/assets/129017064/c6f00b67-8629-44dc-8f70-5fbf0e583cd4)

      
      --> $로 시작함 
      영문,숫자, - , _ ,만 사용할 수 있지만 숫자로 시작할 수 없음.
      
# 💜 Partials(파샬)
      
      관련된 것끼리 묶어서 분리/ 소스에 반복되는 부분들을 분리 분산시켜 모듈화 시키는 기능
      
      * Partials의 파일명은 _로 시작하며
      * 불러들일 때에는 @import '파일명'  이때 파일명에 _는 포함시키지 않고, 확장명도 포함시키지 않는다.
      
      scss는 _로 시작하는 파일은 컴파일하지 않는다.
      
![image](https://github.com/hyejin192/sass/assets/129017064/a6307cc0-94b6-4c40-8db5-67fc890b6084)

## @import

      변수이름이 중복될 땐 아래의 것이 적용된다
![image](https://github.com/hyejin192/sass/assets/129017064/3824ee23-de64-4e00-aa4e-893c98096a99)


## @use 

      변수이름이 같을 땐 에러발생, @use를 사용할 땐 앞에 파일명을 추가해서 파일명.변수명으로 입력
![image](https://github.com/hyejin192/sass/assets/129017064/dce1b39f-3aa8-4619-84eb-5c3528227c61)


      
      
 
   
