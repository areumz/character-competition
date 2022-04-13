#  :pushpin: character-competition
> 멋사 FE 스쿨 캐릭터 경진대회
![image](https://user-images.githubusercontent.com/84116709/163120238-38feec48-3782-42eb-8661-179aeecc0147.png)   
[움직이는 캐릭터 확인하기](https://irrpl-ar.github.io/character-competition/)

</br>

## 1. 제작 기간 & 참여 인원
- 2022년 04월 11일 ~ 04월 13일
- 개인 프로젝트

</br>

## 2. 사용 기술
#### `Front-end`
  - HTML/CSS

</br>

## 3. 핵심 기능

* HTML, CSS만을 사용하여 만든 간단한 캐릭터
* 얼굴 부분을 귀 / 무늬 / 눈 / 코 & 입 부분으로 나누어 작업
* 귀와 얼굴이 일정한 시간 간격에 따라 움직이도록 애니메이션 적용

</br>

## 4. 디버깅
### 각종 디버깅
<details>
<summary>gh-pages 배포 관련 문제</summary>
<div markdown="1">
* 처음에 ```Character_KAR.html``` 이런식으로 html 파일명을 줘서 배포를 시도했기 때문에   
  오류 문구에서 ```index.html```이 없다는 것을 발견함
* index.html로 파일명을 고치고 다시 배포하니 해결됨
</div>
</details>
    
</br>

<details>
<summary>기타 CSS 관련</summary>
<div markdown="1">
* 이번 캐릭터는 HTML, CSS를 활용하여 얼굴 부분만 간단히 캐릭터를 만들었기 때문에,   
  크게 어려운 오류 사항은 없었음

```
/* css */
border-top-left-radius: 80%;
border-top-right-radius: 80%;
border-bottom-left-radius: 100%;
border-bottom-right-radius: 100%;
```

* 위와 같이 세밀하게 border-radius를 조절해서 모양을 만들어주는 것은 처음 사용해봄
  
```
border-bottom: 36px solid #000;
border-left: 18px solid transparent;
border-radius: 50%;
border-right: 18px solid transparent;
```
  
* 위와 같이 삼각형 만들고, 방향만 조절하여 무늬 만들어줌

</div>
</details>
    
</br>

## 5. 회고 / 느낀점
> HTML, CSS로 캐릭터를 만들어보는 것은 처음이었는데, CSS를 다양하게 활용하는 방법을   
  조금 더 배운 것 같다.   
  이번에는 간단히 얼굴만 만들어봤지만 다음에는 배경과 몸까지 만들어봐야겠다!

