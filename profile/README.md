# 📌 간편한 벌금 관리의 시작, 소심한 총무
![KakaoTalk_Photo_2023-12-20-21-24-51](https://github.com/so-sim/front/assets/95389265/ef01c999-2b41-4b9b-922d-220ce655db6c)


동아리, 스터디 등 여러 모임을 운영할 때 빠질 수 없는 벌금!

그런데, 오히려 벌금 때문에 골머리를 앓고 계시지는 않나요?

벌금 관리 시 생기는 모든 불편함,

이제 소심한 총무에서 해결해보세요.


> 

# 주요 기능
- 벌금 템플릿
  - 장부형 벌금 관리 템플릿
  - 벌금 내역 필터링
  - 벌금 관리
  - 벌금 상세 관리
  - 납부 요청 기능
- 모임 관리
- 멤버
  - 멤버 관리
  - 총무 넘기기
  - 멤버 초대
  - 멤버 검색
- 벌금 알림
  - 알림 설정 (납부일, 반복 주기 설정)
  - 알림 기능
- 카카오 로그인
  - access token, refresh token
- 모바일 반응형 및 적응형


## 메인 페이지
<div align="center" >
  <img width="45%" alt="image" src="https://github.com/so-sim/.github/assets/95389265/c4c39367-6fb5-48c3-9ab7-08c3f10f9baf">
  <img width="45%" alt="image" src="https://github.com/so-sim/.github/assets/95389265/e6cc83bb-ff76-4487-a217-2220ef550c4d">
</div>

- 모임 만들기
  - 모임 만들기 모달을 통해 모임 생성
- 모임 리스트
  - 무한스크롤로 참여 모임 리스트 불러오기



## 모임 상세 페이지(캘린더)
<div align="center" >
<img width="45%" alt="스크린샷 2023-12-27 오후 3 12 36" src="https://github.com/so-sim/.github/assets/95389265/1ab0053d-f2bf-435d-875a-970280a136c8">
<img width="45%" alt="스크린샷 2023-12-27 오후 3 13 35" src="https://github.com/so-sim/.github/assets/95389265/e64b544f-78a7-4c93-a807-1f0bca5123d6">
</div>

- 모임의 벌금 장부를 날짜별 태그 형태로 확인
- 날짜 클릭 시, 해당 날짜의 벌금 장부로 이동
- **(총무)** 내역 추가 기능

<br/>

## 모임 상세 페이지(벌금 장부)


### 필터링

<div align="center" >
<img width="45%" alt="스크린샷 2023-12-27 오후 3 13 43" src="https://github.com/so-sim/.github/assets/95389265/d5e24d9b-643a-47e3-af80-8fa833da38d2">
<img width="45%" alt="스크린샷 2023-12-27 오후 3 13 52" src="https://github.com/so-sim/.github/assets/95389265/b4cb6949-8973-47a1-b753-cf40e440b8b6">
</div>

- 월간, 주간, 일간, 상세 기간 버튼으로 원하는 날짜의 내역을 필터링
  - 날짜 우측의 화살표를 통하여 필터링 단위별 날짜 이동 (ex. 월간 필터링 중, 화살표 클릭 시 한 달씩 이동)
- 캘린더에도 필터링된 날짜 표시


<br/>

<div align="center" >
<img width="45%" alt="스크린샷 2023-12-27 오후 3 13 57" src="https://github.com/so-sim/.github/assets/95389265/1ef1d190-4735-495f-88e4-46c30e81925f">
<img width="45%" alt="스크린샷 2023-12-27 오후 3 14 05" src="https://github.com/so-sim/.github/assets/95389265/3b268638-5f2d-480c-8559-9fac4851f138">
</div>

- 필터 버튼을 이용하여 납부여부 상태별 필터링
- 팀원 검색을 통하여 특정 팀원의 벌금 장부 필터링

<br/>

### 납부여부 상태 변경

<div align="center" >
  <img width="45%" alt="스크린샷 2023-12-27 오후 3 15 10" src="https://github.com/so-sim/.github/assets/95389265/123eff03-35df-4d8d-aa2f-de7e0910af4a">
  <img width="45%" alt="스크린샷 2023-12-27 오후 3 20 59" src="https://github.com/so-sim/.github/assets/95389265/8a3fad18-6d35-4ef2-8da4-2d46f5d20151">
</div>

- (총무) 리스트에서 모든 팀원 및 자신의 납부여부 상태 변경 가능

- (팀원) 리스트에서 자신의 내역만 납부여부 상태 변경 가능
  - **납부 전**일 경우에만 **승인 대기**상태로 변경 가능
    
<br/>

### 체크박스

<div align="center" >
  <img width="100%" alt="스크린샷 2023-12-27 오후 3 14 21" src="https://github.com/so-sim/.github/assets/95389265/130311c6-06ab-4123-8a9b-bd4a6d208fb4">
</div>

- 체크박스 툴킷을 통해 체크박스 컨트롤 및 변경/요청 가능
  - (총무) 납부여부 변경 / 납부 요청 가능
  - (팀원) '납부 전'상태의 자신의 내역 납부여부 변경 가능
- 체크한 벌금 내역의 합계

<div align="center" >
  <img width="45%" alt="스크린샷 2023-12-27 오후 3 16 28" src="https://github.com/so-sim/.github/assets/95389265/5cd3570e-0f04-43f8-95c0-7a6fa66d1151">
  <img width="45%" alt="스크린샷 2023-12-27 오후 3 17 03" src="https://github.com/so-sim/.github/assets/95389265/3ec0302d-486e-44bc-ba98-cf60c32b1f30">
</div>

- 여러 건에 대한 납부여부 변경 및 납부 요청 시 요청 전 상세내역 확인
- 변경하기 / 요청하기 버튼 클릭 시, 선택한 건에 대하여 일괄 변경/요청

### 상세 납부내역

<div align="center" >
  <img width="45%" alt="스크린샷 2023-12-27 오후 3 17 42" src="https://github.com/so-sim/.github/assets/95389265/133854e3-adc0-4474-bf8d-18867bec1588">
  <img width="45%" alt="스크린샷 2023-12-27 오후 3 18 52" src="https://github.com/so-sim/.github/assets/95389265/58f48f82-f813-4efb-b974-e0db63c63e88">
</div>

- 벌금장부 리스트 클릭 시, 납부내역의 상세 정보 확인
  - (총무) 납부내역 수정, 삭제
  - (팀원) '납부 전'인 자신의 납부 내역 상태 변경




<img width="1476" alt="툴팁" src="https://github.com/so-sim/.github/assets/95389265/c03e03a1-98a0-4ba4-8b1f-1a6d6fdc6a4c">


### 모임 설정 모달




<div align="center" >
  <img width="20%" alt="스크린샷 2023-12-27 오후 5 08 07" src="https://github.com/so-sim/.github/assets/95389265/0c7f7ac8-01d6-4a07-8e17-b1981843142f">
  <img width="20%" alt="스크린샷 2023-12-27 오후 5 06 26" src="https://github.com/so-sim/.github/assets/95389265/d13128e3-73be-4902-8cdd-36d813971fdf">
  <img width="20%" alt="스크린샷 2023-12-27 오후 5 06 31" src="https://github.com/so-sim/.github/assets/95389265/adc06b9b-cb4d-411b-986b-e92d7dc4c4c9">
  <img width="20%" alt="스크린샷 2023-12-27 오후 5 06 35" src="https://github.com/so-sim/.github/assets/95389265/fadcff71-eb50-4b35-bfdc-be0c1745fcce">
</div>




### 알림 기능 


## 멤버 관리 페이지

<div align="center" >
<img width="45%" alt="스크린샷 2023-12-27 오후 3 20 10" src="https://github.com/so-sim/.github/assets/95389265/7289dc66-6ab2-402a-8e63-3f18a8a603d1">
<img width="45%" alt="스크린샷 2023-12-27 오후 3 20 14" src="https://github.com/so-sim/.github/assets/95389265/0eaed399-562f-406a-b061-43083ce0bb5a">
</div>

- (총무) 총무 넘기기 버튼을 클릭하여 다른 팀원에게 총무 넘기기

## 모바일

- 웹에서 사용하던 모임 생성, 내역 추가하기 모달 -> 모바일 페이지로 변경
- 드롭다운 -> 바텀시트로 변경
- 벌금 장부 페이지네이션 -> 무한 스크롤로 변경

### 메인 페이지
<div align="center" >
  <img width="18%" alt="스크린샷 2023-12-27 오후 3 22 22" src="https://github.com/so-sim/.github/assets/95389265/fd884857-f499-47d3-96e2-ebf225b8da23">
  <img width="18%" alt="스크린샷 2023-12-27 오후 3 25 08" src="https://github.com/so-sim/.github/assets/95389265/e580ac22-3366-4d5d-b4da-1b91cd42e52f">
  <img width="18%" alt="스크린샷 2023-12-27 오후 3 22 58" src="https://github.com/so-sim/.github/assets/95389265/4dd79eb5-b63b-4786-b2ac-e52e2bf0d5db">
</div>


- 메인페이지, 모임 생성 모달 -> 모임 생성 페이지로 변경


### 모임 상세 페이지
<div align="center" >
  <img width="18%" alt="스크린샷 2023-12-27 오후 3 23 12" src="https://github.com/so-sim/.github/assets/95389265/bb4369e6-9737-4802-9cd3-dbb65d102e06">
  <img width="18%" alt="스크린샷 2023-12-27 오후 3 23 29" src="https://github.com/so-sim/.github/assets/95389265/411e7095-66a4-4891-904c-c174011fba77">
</div>

- 모임 초대하기 모달
- 가입된 모임 리스트 확인 가능


### 벌금장부 페이지

<div align="center" >
  <img width="18%" alt="스크린샷 2023-12-27 오후 3 23 35" src="https://github.com/so-sim/.github/assets/95389265/bc2b9be2-520c-49d9-8b80-e89db916e805">
  <img width="18%" alt="스크린샷 2023-12-27 오후 3 24 34" src="https://github.com/so-sim/.github/assets/95389265/b49cfd2c-046e-4d68-a7be-af5859c80497">
  <img width="18%" alt="스크린샷 2023-12-27 오후 3 23 57" src="https://github.com/so-sim/.github/assets/95389265/8357c6ee-bec8-4d69-93dc-e12002d7bcc6">
  <img width="18%" alt="스크린샷 2023-12-27 오후 3 24 43" src="https://github.com/so-sim/.github/assets/95389265/6deb7703-129b-4f65-8b97-f3ddfbf457d2">
  <img width="18%" alt="스크린샷 2023-12-27 오후 3 24 51" src="https://github.com/so-sim/.github/assets/95389265/8f1ef723-4e3e-47ed-8f85-b5e9caa0b8ac">
</div>
- 캘린더와 벌금 장부 리스트 (바텀시트 형태로 구현)

<div align="center">
  <img width="30%" src="https://github.com/so-sim/.github/assets/95389265/0a0d4ba0-1a6b-45c3-8cbd-e711975005d7">
</div>

- 벌금장부 스크롤 시, 상단에 날짜 고정



### 알림 페이지

<div align="center" >
  <img width="18%" alt="스크린샷 2023-12-27 오후 3 25 48" src="https://github.com/so-sim/.github/assets/95389265/bf468b40-fd75-423e-ab89-c18114239fd4">
  <img width="18%" alt="스크린샷 2023-12-27 오후 3 25 54" src="https://github.com/so-sim/.github/assets/95389265/1d740d56-dd7f-463f-9c62-f29684366f49">
  <img width="18%" alt="스크린샷 2023-12-27 오후 3 26 07" src="https://github.com/so-sim/.github/assets/95389265/1cb7506d-8824-4cae-934e-d3991efe1c65">
</div>

- 알림 아이콘 터치 시, 알림페이지로 이동
- 해당 알림에 대한 페이지로 이동
  - 총무 변경 알림: 멤버관리 페이지
  - 벌금 주기 알림: 알림이 보내진 시점에서 납부 전, 승인 대기 다중 변경 페이지
  - 납부 요청 알림: 납부요청 보내진 장부 변경 페이지



### 초대장 페이지

초대하기 링크를 통해 간편하게 모임에 가입할 수 있습니다.

<div align="center" >
  <img width="18%" alt="스크린샷 2023-12-27 오후 3 30 17" src="https://github.com/so-sim/.github/assets/95389265/a9175850-50b1-4eb9-8b97-f264e814d2dd">
  <img width="18%" alt="스크린샷 2023-12-27 오후 3 30 30" src="https://github.com/so-sim/.github/assets/95389265/932a485e-2c03-49e1-97c1-84abbe450a7f">
  <img width="18%" alt="스크린샷 2023-12-27 오후 5 40 24" src="https://github.com/so-sim/.github/assets/95389265/3d97c6bb-d4aa-4a96-9d83-1b90326897f2">
</div>

- 초대하기 링크로 진입 시, 해당 모임의 초대장 페이지로 이동
- 모임에 가입되어 있지 않은 경우:
  - 닉네임 입력 후 모임 가입 완료 시, 모임 상세 페이지로 이동
- 로그인 및 회원가입이 되어 있지 않은 경우:
  - 로그인 및 회원가입 초대장 페이지로 리다이렉트

## 🧑‍🤝‍🧑 Team - Sosim
<table>
  <tr>
    <td align="center" colspan="1">
      <b>PM</b>
    </td>
    <td align="center" colspan="1">
      <b>Design</b>
    </td>
    <td align="center" colspan="2">
      <b>Frontend</b>
    </td>
    <td align="center" colspan="2">
      <b>Backend</b>
    </td>
  </tr>
  <tr>
    <td>
      <img src="https://avatars.githubusercontent.com/u/126806581?v=4" width="120px" height="120px"/>
    </td>
    <td>
      <img src="https://avatars.githubusercontent.com/u/94945843?v=4" width="120px" height="15%"/>
    </td>
    <td>
      <img src="https://avatars.githubusercontent.com/u/95389265?v=4" width="120px" height="15%"/>
    </td>
    <td>
      <img src="https://avatars.githubusercontent.com/u/45344418?v=4" width="120px" height="15%"/>
    </td>
    <td>
      <img src="https://avatars.githubusercontent.com/u/123621015?v=4" width="120px" height="15%"/>
    </td>
    <td>
      <img src="https://avatars.githubusercontent.com/u/76610333?v=4" width="120px" height="15%"/>
    </td>
  </tr>
  <tr>
    <td align="center">
      <a>
      유나경
      </a>
    </td>
    <td align="center">
      <a>
      윤가람
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/Jong1co">
      박종현
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/jma1020">
      김정민
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/Park-Jaemin">
      박재민
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/HyeonKyo">
      김현교
      </a>
    </td>
  </tr>
</table>

## 📆 Session
<table> 
  <tr>
    <td align="center" colspan="1">
      <b>1차</b>
    </td>
    <td align="center" colspan="1">
      <b>2차</b>
    </td>
    </tr>
  <tr>
    <td>
      2023-01-18 ~ 2023-04-12
    </td>
    <td>
      2023-06-13 ~ 2023-09-11
    </td>
  </tr>
</table>

## 🔗 Link
<b>Homepage - </b> [소심한총무](https://sosim-manager.com)
<br>
<b>Detail Intro - </b> [Notion](https://steadfast-car-5c9.notion.site/6e5b2e9a2abb4cb3bfb32fd34f326b61)
<br>
<b>FE Repository - </b> [React, TypeScript](https://github.com/so-sim/front)
<br>
<b>BE Repository - </b> [Spring, Java](https://github.com/so-sim/server)
