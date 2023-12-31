# vite를 이용한 포트폴리오 사이트 만들기

## vite를 사용하는 이유

1.  느렸던 소스 코드 갱신
    기존의 번들러 기반으로 개발을 진행할 때, 소스 코드를 업데이트 하게 되면 번들링 과정을 다시 거쳐야 했었습니다. 따라서 서비스가 커질수록 소스 코드 갱신 시간 또한 선형적으로 증가하게 됩니다.

## 구현

-   smooth 효과 적용 https://lenis.studiofreight.com/
-   자바스크립트 메뉴 클릭 이동 효과 적용
-   gsap를 이용한 가로스크롤 효과
-   JavaScript 모듈 기능 적용
-   웹표준 준수를 위한 스킵 메뉴 및 aria, role 적용
-   vite 빌드 작업 'npm run build'
-   net

1. 폰트 적용
1. [vite](https://ko.vitejs.dev/guide/)

## 트러블 슈 팅

-   gsap scrollTrigger 사용 가로스크롤 모드를 적용할 때 원치 않는 여백이 발생함
    동적으로 생기는 여백에 색을 줄것이 아니라 body와 html 태그에 전체적으로 적용해 여백을 없앴음
-   gsap 활용 및 첫 install시 버전을 확인 잘 할 것.
<details>
<summary>-git 업로드 설정;</summary>
-   error: failed to push some refs to 'origin'
-   초기 설정시 origin main을 사용하는 방법은 잘못되었음
<details>
