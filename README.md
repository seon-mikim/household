# 프로젝트 소개
### 프로젝트 명 
- House Hold(가계부)
### 프로젝트 기간 
- 2023.08.21(월)~
### 프로젝트 설명 
- 자신이 소비한 항목들을 리스트로 볼 수 있는 가계부 웹 어플리케이션을 만들기.
### 배포 사이트 
(배포사이트)[https://vercel.com/xiuxiubok/house-hold-account]
### 요구사항 

1. create-react-app 으로 프로젝트를 세팅.
2. 다음과 같은 항목들을 form input을 통해 입력을 받음.
    - 이름 : string
    - 가격 : number
    - 유형 : string
    - 구입 날짜 : date
    - 메모 : string
        - 체크박스로 체크가 된 경우만 메모 input을 보여주고 값을 받음.
    - 재구매 의사 : boolean
        - 라디오 버튼을 통해 구현
3. 입력받은 소비 항목들은 최신 순서대로 리스트로 보여짐.
4. 유형별 필터를 통해 유형에 맞춰 필터링된 리스트를 볼 수 있음.
5. 정렬 기준을 다음과 같이 가지고 정렬해 줄 수 있음.
    1. 가격 높은 순
    2. 가격 낮은 순
    3. 최신 순
    4. 오래된 순
6. 기간을 정해서 해당 기간에 소비한 내역만 볼 수 있음.

### 주의 사항 
1. HTML과 CSS는 와이어프레임을 참고해서 레이아웃이 구분될 정도로만 만들어 주시면 됨.
2. css 클래스명은 BEM 방식을 따르기를 권장.
3. 주어진 프로젝트 설명을 명확하게 이해하고 해당 요구사항대로 정확하게 구현을 하는 것에 집중.
4. state, props, event handler를 적절하게 목적에 맞게 사용.
5. 하나의 컴포넌트는 하나의 역할을 하는 방향으로 만들기.
6. 변수명, 함수명을 명시적으로 바로 잘 이해할 수 있게 작성.
