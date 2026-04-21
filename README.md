# YD MES PROJECT
<img width="1891" height="939" alt="메인" src="https://github.com/user-attachments/assets/4d1e5bff-d2dd-426f-bdac-2ad78dee168d" />

## 바로가기

<p align="center">
  <a href="#프로젝트-개요"><kbd>📘 프로젝트 개요</kbd></a>
  &nbsp;&nbsp;
  <a href="#내-파트"><kbd>🧩 내 파트</kbd></a>
  &nbsp;&nbsp;
  <a href="#프로젝트-소감"><kbd>📝 프로젝트 소감</kbd></a>
  &nbsp;&nbsp;
  <a href="#Project-Structure"><kbd>📁 Project Structure</kbd></a>
</p>

---

## 프로젝트 개요

본 프로젝트는 **라면 공장의 생산 공정을 대상으로 한 MES 기반 생산 관리 시스템**입니다.  
생산 계획, 작업 지시, 공정 진행, 설비 및 생산 실적 데이터를 실시간으로 수집·관리하여  
**생산 과정의 가시성과 효율성**을 향상시키는 것을 목표로 구현되었습니다.

### 개발 일정
- **2025.12.03 ~ 2025.12.09**

## 팀 구성 및 역할

<!-- 팀원 소개 테이블 -->
<table border="1" cellpadding="12" cellspacing="0" align="center" >
  <tr>
    <th align="center">도우서</th>
    <th align="center">배진욱</th>
    <th align="center">김동우</th>
    <th align="center">박희찬</th>
    <th align="center">권수민</th>
  </tr>
  <tr>
    <td align="center">
      <img  width="120" alt="male" src="https://github.com/user-attachments/assets/4c713a36-ac69-4107-bf2e-e7de21af0f90" />
    </td>
    <td align="center">
      <img width="120" alt="male" src="https://github.com/user-attachments/assets/4c713a36-ac69-4107-bf2e-e7de21af0f90" />
    </td>
    <td align="center">
      <img width="120" alt="male" src="https://github.com/user-attachments/assets/4c713a36-ac69-4107-bf2e-e7de21af0f90" />
    </td>
    <td align="center">
      <img width="120" alt="male" src="https://github.com/user-attachments/assets/4c713a36-ac69-4107-bf2e-e7de21af0f90" />
    </td>
    <td align="center">
      <img width="120" alt="female" src="https://github.com/user-attachments/assets/8d5708ba-b9f8-41e6-bd47-7c5e777a0088" />
    </td>
  </tr>
  <tr>
    <td align="center">생산</td>
    <td align="center">DB관리 </br> 생산</td>
    <td align="center">기준정보</td>
    <td align="center">기준정보</td>
    <td align="center">주문</td>
  </tr>
</table>
<table border="1" cellpadding="12" cellspacing="0" align="center" >
  <tr>
    <th align="center">성찬혁</th>
    <th align="center">정재은</th>
    <th align="center">박세민</th>
    <th align="center">송승일</th>
    <th align="center">김현태</th>
  </tr>
  <tr>
    <td align="center">
      <img width="120" alt="male" src="https://github.com/user-attachments/assets/4c713a36-ac69-4107-bf2e-e7de21af0f90" />
    </td>
    <td align="center">
      <img width="120" alt="female" src="https://github.com/user-attachments/assets/8d5708ba-b9f8-41e6-bd47-7c5e777a0088" />
    </td>
    <td align="center">
      <img width="120" alt="male" src="https://github.com/user-attachments/assets/4c713a36-ac69-4107-bf2e-e7de21af0f90" />
    </td>
    <td align="center">
      <img width="120" alt="male" src="https://github.com/user-attachments/assets/4c713a36-ac69-4107-bf2e-e7de21af0f90" />
    </td>
    <td align="center">
      <img width="120" alt="male" src="https://github.com/user-attachments/assets/4c713a36-ac69-4107-bf2e-e7de21af0f90" />
    </td>
  </tr>
  <tr>
    <td align="center">주문</td>
    <td align="center">자재</td>
    <td align="center">자재</td>
    <td align="center">품질</td>
    <td align="center">품질</td>
  </tr>
</table>


---

## 개발 환경
```
[FRONT]    JavaScript, Vue.js, HTML, CSS  
[BACK]     Express.js  
[DATABASE] MariaDB  
[TOOL]     Git, NAVER Cloud Platform, VS Code
```

## 프로세스 흐름도

<img width="1203" height="679" alt="image" src="https://github.com/user-attachments/assets/1e14d6f1-058f-42ba-a399-3da689bc86cd" />

---

<p align="center">
  <a href="#프로젝트-개요"><kbd>📘 프로젝트 개요</kbd></a>
  &nbsp;&nbsp;
  <a href="#내-파트"><kbd>🧩 내 파트</kbd></a>
  &nbsp;&nbsp;
  <a href="#프로젝트-소감"><kbd>📝 프로젝트 소감</kbd></a>
  &nbsp;&nbsp;
  <a href="#Project-Structure"><kbd>📁 Project Structure</kbd></a>
</p>

---

## 내 파트

저희 프로젝트에서 주문의 출고 파트를 담당하였습니다.
주문서를 기반으로 제품의 출고 요청을 진행하고,
현재 출고 요청을 조회하여 출고할 제품 수량을 입력 후 실출고를 진행합니다.

실출고 수량 입력시 실시간으로 계산되어 재고 파악이 가능하도록 설계하였습니다.

---

## 내 파트 주요 페이지별 기능

#### 출고 조회
<p align="center">
<img width="1920" height="919" alt="출고조회" src="https://github.com/user-attachments/assets/aeec1a96-7cf4-4dd8-bfd8-614c47fe0a0c" />
</p>

+ 현재 출고 요청에 대한 상태를 조회하고 다양한 검색조건으로 원하는 출고 정보를 찾을 수 있습니다.
+ 원하는 출고 정보을 선택하여 엑셀 파일로 다운로드가 가능합니다.

---

#### 출고 요청 상세
<p align="center">
<img width="1920" height="919" alt="출고요청상세" src="https://github.com/user-attachments/assets/eea090e6-f60b-47f2-8498-96c4e224740d" />
</p>

+ 출고 조회 페이지에서 출고 정보 클릭시 해당 상세 페이지에서 상세 정보를 확인할 수 있습니다.

---

#### 출고 요청
<p align="center">
<img width="1920" height="920" alt="출고요청 불러온 주문" src="https://github.com/user-attachments/assets/83e76d80-631d-4a41-9e53-120e644b39b8" />
</p>

+ 주문정보를 불러와 출고 요청을 진행하거나 출고 요청을 불러와 요청을 수정할 수 있습니다.

---

#### 출고 관리
<p align="center">
<img width="1920" height="919" alt="출고관리 불러온 출고요청" src="https://github.com/user-attachments/assets/7e727cdb-7028-4438-88db-234dc572aa26" />
</p>

+ 출고 요청을 불러와 실출고 수량을 입력하고 실출고를 진행합니다.

---

## 프로젝트 소감
**라면 생산 공정**이라는 구체적인 도메인을 대상으로 MES를 구축하며, 단순한 웹 개발을 넘어 **산업 현장의 업무 프로세스**를 시스템화하는 값진 경험을 했습니다. 주문 정보를 기반으로 출고 요청 및 실출고까지 이어지는 일련의 과정을 구현하면서, 각 공정 단계가 유기적으로 연결되어야 함을 깨달았습니다.

특히 프로젝트 진행 중 데이터베이스 구조와 API 설계에 대해 팀원들과 긴밀히 소통하며 **협업의 중요성**을 다시 한번 느꼈습니다. 실시간 재고 파악 기능 구현을 통해 데이터 정합성의 중요성을 체감했으며, 아쉬운 점으로 남은 '통계 시각화' 부분은 추후 고도화 과정을 통해 보완하여 더욱 완성도 높은 시스템을 만들고 싶다는 목표를 갖게 되었습니다.

---

<p align="center">
  <a href="#프로젝트-개요"><kbd>📘 프로젝트 개요</kbd></a>
  &nbsp;&nbsp;
  <a href="#내-파트"><kbd>🧩 내 파트</kbd></a>
  &nbsp;&nbsp;
  <a href="#프로젝트-소감"><kbd>📝 프로젝트 소감</kbd></a>
  &nbsp;&nbsp;
  <a href="#Project-Structure"><kbd>📁 Project Structure</kbd></a>
</p>

---

## Project Structure

### Client / Server Architecture

<div align="center">
  <table>
    <tr>
      <td align="center" valign="top">
        <b>Client</b><br/>
        <img src="https://github.com/user-attachments/assets/257ac449-1b3c-4361-8918-30f3f4aeca70" width="420"/>
      </td>
      <td align="center" valign="top">
        <b>Server</b><br/>
        <img src="https://github.com/user-attachments/assets/ea9f0251-1d27-4328-ab6a-21e3cc585082" width="420"/>
      </td>
    </tr>
  </table>
</div>

### MY Client

```text
frontend
└── src
     └── views
          └── release
               ├── 📄 ForwardingApproval.vue        // 신청현황
               ├── 📄 ForwardingCheck.vue           // 담당자 권한 이전
               ├── 📄 ForwardingDetail.vue          // 이벤트 계획 승인 요청 목록
               └── 📄 ForwardingManagement.vue      // 이벤트 결과 승인 요청 목록
```
### MY Server Architecture

```text
backend
├── database
│    ├── sqls
│    │    └── release
│    │         └── 📄 fwdSQL.js        // 출고파트 쿼리
├── routers
│    ├── release
│    │    └──📄 fwdRouter.js           // 출고파트 라우터
└── services
     └── release
          └──📄 fwdService.js          // 출고파트 서비스
```
