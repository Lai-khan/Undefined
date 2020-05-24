# 프로젝트 이름
Undefined (미정)

## 프로젝트 설명
대학생 프로젝트 모임(IT)

같이 프로젝트를 하고 싶은데 사람 구하기가 어렵다.

`프로젝트를 같이 할 만한 사람을 구할 수 있는 커뮤니티가 있다면 어떨까?` 라는 생각으로 만들어 보는 프로젝트.

이용자들은 하고 싶은 프로젝트에 대해 설명하고 구하고 싶은 사람의 조건을 설정하고 그에 맞는 사람을 구할 수 있다.

## 기능
1. 로그인

    네이버, 카카오, 구글, 페이스북 로그인이 가능하게 할 예정

2. 글쓰기

    하고 싶은 프로젝트에 대해 설명하고, 구하고 싶은 사람의 조건을 명확히 나타낼 수 있는 글을 간단하게 작성할 수 있어야한다.
    
    모바일에 맞는 UI

3. 검색

    크게 검색 기능과 필터 기능으로 나뉜다.
    
    검색 기능은 검색창에 검색어를 입력하면 그걸 기준으로 게시글을 찾아주고,
    
    필터 기능은 특정 카테고리에 대해 필터를 선택하면 해당 필터에 해당되는 게시글들만 보여준다.

4. 프로필 설정

    자신을 잘 나타낼 수 있는 자기소개와, 지금까지 경험했던 프로젝트들, 그리고 깃허브나 블로그 주소, 사는 거주지, 주요 기술 스택(할 수 있는 것들) 등을 나타낼 수 있는 란이 있어야 한다.
    
    한마디로 포트폴리오란이라고 보면 된다.
    
    개발자, 디자이너, 기획자 모두에게 편리하고 알맞아야 한다.

5. 채팅

    간단한 채팅을 할 수 있어야 한다.
    
    채팅은 이 서비스의 주요기능은 아니지만 사람을 구하는데 간단한 대화는 필요하다고 생각해 간단한 채팅 기능을 구현해 볼 예정이다.

## 화면 설계서
간단하게 그려본 것으로 세부적인 디자인은 미정

### 로그인 화면
<img src="https://user-images.githubusercontent.com/40736969/82752612-249ee780-9dfa-11ea-9e58-7fafe3cdeb39.png"  width="360" height="600">

### 홈 화면
<img src="https://user-images.githubusercontent.com/40736969/82752615-2668ab00-9dfa-11ea-98a4-6e0078db0daa.png"  width="360" height="600">

### 글 화면
<img src="https://user-images.githubusercontent.com/40736969/82752617-28326e80-9dfa-11ea-89d7-122e0d6a70a2.png"  width="360" height="600">

### 글쓰기 화면
<img src="https://user-images.githubusercontent.com/40736969/82752618-29639b80-9dfa-11ea-8808-f50469320d3d.png"  width="360" height="837">

### 채팅 목록 화면
<img src="https://user-images.githubusercontent.com/40736969/82752620-2b2d5f00-9dfa-11ea-9adc-7a0e1732bca0.png"  width="360" height="600">

### 채팅 화면
<img src="https://user-images.githubusercontent.com/40736969/82752622-2cf72280-9dfa-11ea-96d1-617ce675e6fd.png"  width="360" height="600">

### 프로필 화면
<img src="https://user-images.githubusercontent.com/40736969/82752625-2f597c80-9dfa-11ea-9eeb-f8091ac76fb5.png"  width="360" height="600">

## 아키택쳐
하이브리드 앱이나 웹 앱으로 만들 생각이다. 자세한 건 미정

생각하고 있는 기술 스택은

- React / React Native
- Node.js / Express
- socket.io
- Java Spring
- Redis
- DB는 고민중

## 깃헙 정책
`master` <- `develop` <- `feature/기능 이름`
