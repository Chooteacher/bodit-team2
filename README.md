# Bodit 2team ❤️‍🔥

### **[배포링크](https://SeanKim05.github.io/bodit-team2/)**

## JUSTCODE 6기 기업협업 1주차 2번째 과제-바딧- 2팀

<br />

## 1. 개발 기간 🗓

- **개발 기간** : 2022.10.07 ~ 2022.10.09(3일)
  <br />
  <br />

## 2. 팀원 및 협업 방식 🤹

**팀원**

- 김유현
- 박기호
- 봉원희
- 이은지
- 서지원

**협업 방식**

- **[팀 노션](https://www.notion.so/wecode/aae6c129b9c448c0a0ded1c5fb783437?p=602aa7e403c545d2a05f178d6424a37a&pm=c)**
  <br />
  <br />

## 3. 프로그램 실행 방법 및 파일 프로젝트 구조 🚧

### 프로그램 실행 방법

<br />

1.  터미널을 키고 원하는 폴더 경로로 이동해 레포지토리를 클론 받습니다.

```
git clone https://github.com/SeanKim05/bodit-team2.git
```

<br />

2.  클론이 다 받아지고 나면 패키지를 다운 받습니다.

```
npm i
```

<br />

3.  프로젝트를 실행합니다.

```
npm start
```

<br />

4. 브라우저가 켜지고 프로젝트를 확인 할 수 있습니다.
   <br />
   <br />

### 파일 프로젝트 구조

- `public/data`: Mock 데이터 폴더
- `src/pages/main`: 메인 페이지 파일 폴더
- `src/pages/graph`: 그래프 페이지 파일 폴더
- `src/styles`: 전역 스타일 관리 폴더
   <br />
   <br />

## 4. 적용 기술 및 구현 기능 🛠

<br />

### 4-1. 적용 기술

- JavaScript
- React.js
- react-router-dom
- styled-components
- fortawesome
- chart.js (차트 라이브러리)
- react-chartjs-2
- eact-zoom-pan-pinch (확대 축소 버튼 라이브러리)
- react-calendar (달력 라이브러리)
- react-datepicker
- date-fns
- moment
- react-csv (csv 라이브러리)
- gh-pages (배포라이브러리)

<br />

### 4-2. 구현 기능

- ✅ 첫번째 페이지 _(/ )_
<br />

![table](https://user-images.githubusercontent.com/105857105/196739650-b3638413-75e9-4bf5-ad37-53400b14ef9d.png)

  <br />

- ✅ 두번째 페이지 _(/graph)_

<br />

![graph](https://user-images.githubusercontent.com/105857105/196739659-fc412624-d496-4d2a-8528-b4a8ae7a81e3.png)

  <br />

✨ 내가 작업한 기능

- 첫번째 페이지
    - 테이블
      - 메인화면 UI
      - 필터가 없는 테이블의 각 th 클릭 시 정렬
      - 필터가 있는 테이블의 th는 sort img 클릭시 정렬
     
     <br />
     
✨ 느낀점

- 메인화면 UI를 빨리 구현해서 팀원분들에게 넘겨줘야 작업이 가능 했는데 별거 아닌 table 이였지만 굉장히 부담스러웠다. 
- 오름/내림차순을 구현을 다 하고 merge까지 해놓은 상태였는데, 필터를 작업하시는 분의 코드와 충돌이 굉장히 많이나 고통스러웠던 기억이 있다...
- 게다가 필터기능을 th를 클릭시 이벤트가 들어가게끔 구현을 해놓아서 오름/내림차순이 작동을 안하는것을 보고 시간이 없을때인지라 눈물을 머금고 필터가 들어간 부분만 sort img를  넣어 기존의 이벤트를 img 태그에 적용했다.
- 디자인적으로 굉장히 간단하게 했지만 기본적인 UI가 조금 아쉬운 마음이 든다. (시간만 더 있었다면...)
