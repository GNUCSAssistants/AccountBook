# AccountBook
 2020 경상대 CS 종합설계및프로젝트

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

### 4월 3일
#### vuetify에서 이미 만들어져있던 코드인 complex 레이아웃 적용
#### 메인화면 작업 시작

### 4월 4일
#### 메인페이지 대충 만들어놓음
#### 화면을 상단바, moneyState, calendar, moneyDetail, footer로 나눔
#### 화면 레이아웃 %로 수정
#### moneyState 레이아웃 1차완성

### 4월 5일
#### moneyDetail 아이콘빼고 레이아웃 작업 1차완료
#### 달력 구현중

### 4월 6일
#### 메인부 UI 1차 완성

### 4월 9일
#### Login화면 구현. App.vue의 하위 컴포넌트라서 그런지 css적용이 꽉 차게 안되서 아쉬움. 그래도 그렇게 안 이쁜건 아니라서 그대로 둘 예정
#### 데이터 깔끔히 정리. 상위 컴포넌트인 Main에 집중
#### moneyDetail이 수입일 경우, 파란색이 뜨도록 코딩함

### 4월 12일
#### 로그인 화면 대충 만들어놓음.
#### 팀원들에게 php코드 작성 지시
#### DB스키마 검토했음. 수정사항 지시함.

### 4월 19일
#### 로그인과 회원가입 시 입력되는 데이터 바인딩
#### 회원가입 시 비밀번호를 ... 이 아닌 텍스트로 볼 수 있는 버튼 만듦.
#### 일단 서버코드가 없으니 로그인과 회원가입 시도시 실패 알람 뜨도록 만듦
#### 회원가입 시 진행되는 자산과 고정수입, 고정지출 입력부분 만듦. 
#### 삭제와 추가 가능함.
#### ,를 붙여서 화폐보기로 만들려고 했으나, v-for로 구조를 바꾸고 제대로 작동안해서 그냥 내버려둠. 맨 앞 0없애는 것도 마찬가지.
#### 파이차트 적용중. FusionCharts 이용.
#### 클릭했을 때 해당 라벨이 콘솔에 찍히도록 만듬. 이걸로 세부내역을 받아올 예정

### 4월 20일
#### 회원가입부 작업중

### 4월 23일
#### 메인화면 작업중
#### 하단 지출버튼 누를 시 드롭다운메뉴 뜨도록 만듬
#### 생활비 초과시 경고창 ui작업함
#### 지출 입력부 작업중

### 4월 26일 작업내용
#### 통계버튼 클릭 시 통계로 빠지고 아이콘모양 뒤로가기로 바뀜
#### 통계 상세내역 레이아웃만 잡아둠
#### 지출내역 추가 부분 UI코딩함. 
#### 오른쪽 상단 아이콘 누를 시, 메뉴바 뜨게 만듦

### 4월 27일 작업내용
#### 사용자 통계, 목표, 소비유형부 UI코딩
#### 설정부 코딩 진행중

### 5월 3일 작업내용
#### 설정부 UI작업중. 지출 카테고리는 미완성했고 해야할 목록들은 해당 컴포넌트에 메모해둠