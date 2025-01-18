# 🏋️ **프로젝트 : 핏넥서스**

![jsp메인](https://chestnut-blinker-ca6.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2F8cd794c0-c633-4008-b289-af6deeea8c4d%2Ffe1fbb5b-4dc0-461a-96a4-bcdabb325a44%2Fimage.png?table=block&id=169902bd-b12f-80eb-b7b9-cd98b3b4679a&spaceId=8cd794c0-c633-4008-b289-af6deeea8c4d&width=1420&userId=&cache=v2)

---

## 🎥 **프로젝트 발표 영상**  
[**발표 영상 링크**](https://www.youtube.com/watch?v=HG9iWUQFf-4)



---

## 📚 **프로젝트 소개**
- **주제**
    - 스마트 헬스장 통합관리 시스템
    
- **선정 배경**
    - 현대인의 건강과 운동에 대한 관심이 높아짐에 따라 헬스장은 필수적인 생활공간이며 이용자가 더욱 편리하게 헬스장을 이용할 수 있도록 하기 위함
    
- **기획 의도**
    - 기존 헬스장 시스템에 존재하는 **헬스장 등록, PT 예약, 실시간 현황 파악 등의** 어려움을 개선하기 위해 기획하게 되었음
    
- **활용방안**
    - QR 코드를 통한 출입 관리 시스템
    - 원하는 날짜에 본인이 선택하는 PT 예약 시스템
    - 실시간으로 헬스장의 혼잡도 파악
    - 본인만의 스케줄을 계획하는 일정관리
    
- **기대효과**
    - 불필요한 시간을 절감
    - 헬스장 이용 편리성 증대
    - 개인 맞춤 서비스를 강화
    - 동기 부여 형성과 고객 유지율 상승
    - 매출 관리 및 운영 효율성 증대

---

## 👥 **팀 구성**
| **이름**   | **담당 기능**                       |
|-----------|----------------------------------|
| **오승원** | 메인화면구성, 출석체크(QR), 출석내역관리, 출석랭킹조회, 이용권내역조회 |
| **이세진** | 이용권, 트레이너 프로필, 결제, 구매내역, 매출조회 |
| **홍성윤** | 예약기능, 캘린더API연동, 관리자 페이지 레이아웃 |
| **김도현** | 회원관리, 문의사항 게시판, 회원가입 및 로그인, 커스텀 에러페이지 |
| **조하은** | 회원 일정관리, 트레이너 코멘트관리, 캘린더API연동 |

---

## 🗓️ **프로젝트 기간**
###  **2024-11-27 ~ 2024-12-13**

---
## 🚀 **프로젝트 수행 절차**
 ### <span style="color:#FF5733;">1️⃣</span> **주제선정 및 기획 의도 선정**  
 ### <span style="color:#33A1FF;">2️⃣</span> **요구사항, 기능 정의서 작성, 피그마 화면 설계**  
 ### <span style="color:#33FF57;">3️⃣</span> **ERD 설계 DB, 프로젝트 구조 구축**  
 ### <span style="color:#FF33F6;">4️⃣</span> **개발 및 테스트**  
 ### <span style="color:#FFD700;">5️⃣</span> **수정 및 확정, 결과보고서 작성**


---


<summary><h2>🛠️ <strong>개발 환경</strong></h2></summary>
  
  
  ![개발 환경 이미지](https://chestnut-blinker-ca6.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2F8cd794c0-c633-4008-b289-af6deeea8c4d%2Fa15b7295-4884-4d79-a760-47e8a23443c3%2Fimage.png?table=block&id=169902bd-b12f-8054-9a60-fc844af24385&spaceId=8cd794c0-c633-4008-b289-af6deeea8c4d&width=1090&userId=&cache=v2)



---


<summary><h2>📑 <strong>요구사항 정의서</strong></h2></summary>
  
   ![image](https://github.com/user-attachments/assets/6628cdef-0e84-469a-9f1a-c7409b145b70)



---


<summary><h2>🗒️ <strong>기능 정의서</strong></h2></summary>
  
  - 사용자(유저) 기능 정의서
 
    ![image](https://github.com/user-attachments/assets/36f473e1-be4c-412c-aa74-a4ae4850f6ea)  
  - 관리자 기능 정의서

    ![image](https://github.com/user-attachments/assets/6e0eef6f-38a4-46fc-9309-9233e7c01a9a)


---


<summary><h2>🗂️ <strong>ERD</strong></h2></summary>
  
  ![ERD 이미지](https://chestnut-blinker-ca6.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2F8cd794c0-c633-4008-b289-af6deeea8c4d%2F2317d53d-12bb-40e1-bf7e-43a3f29dda8a%2Fimage.png?table=block&id=16b902bd-b12f-8032-8568-e03391399423&spaceId=8cd794c0-c633-4008-b289-af6deeea8c4d&width=1920&userId=&cache=v2)



---

<details>
  <summary><h2>📃 <strong>테이블 정의서</strong></h2></summary>

  **users**  
  ![파일 1](https://drive.google.com/uc?export=view&id=1uIkf6OmogJD5af0uHBwp7YV3TTbpH3VZ)

  **user_auth**  
  ![파일 2](https://drive.google.com/uc?export=view&id=1jN24i-GWXzEaQF1ihnPVtD_BxswsBx_r)

  **trainer_profile**  
  ![파일 3](https://drive.google.com/uc?export=view&id=1TPs7lZxuO-pEYjJHMdNwJWV61aEUtdf9)

  **ticket**  
  ![파일 4](https://drive.google.com/uc?export=view&id=1scpM-FcbpngM4dxbmNXPtbgUdVckzusZ)

  **reservation**  
  ![파일 5](https://drive.google.com/uc?export=view&id=1xvzmCFNDani9r9_2bwRL4lEzRCZBXmIN)

  **qr_code**  
  ![파일 6](https://drive.google.com/uc?export=view&id=18iWrwLE9zu-smJXRqkG0e2l2ZFN8uTqI)

  **plan**  
  ![파일 7](https://drive.google.com/uc?export=view&id=1b2RnAr5tEDigonnXHQxR9BaWqA42da09)

  **persistent_logins**  
  ![파일 8](https://drive.google.com/uc?export=view&id=18N74mHKPW_teWLFvMnrmO_g9BT7kMB_X)

  **file**  
  ![파일 9](https://drive.google.com/uc?export=view&id=1LZ9m864zA8lH-9QELMlB3eMvwYrSozVY)

  **comment**  
  ![파일 10](https://drive.google.com/uc?export=view&id=1XMzew_jB9ZQr48ADICPEvtZIUg27Fw4E)

  **buy_list**  
  ![파일 11](https://drive.google.com/uc?export=view&id=1jBHzorTvyaTU4mbavzbr8hU-AmjM0GAV)

  **board**  
  ![파일 12](https://drive.google.com/uc?export=view&id=1EttYQgue7v7_pV5ST8ZMe9LE25uHIALg)

  **attendance**  
  ![파일 13](https://drive.google.com/uc?export=view&id=1XhCdlUg7401eCwPyEmInVpV7fgyPHMJJ)

  **answer**  
  ![파일 14](https://drive.google.com/uc?export=view&id=1ecTX_u14K37SFcFf8VHYahDJGN8yru5g)

</details>                                                                                                                    

---
&nbsp;
# 📊 **화면 설계서**

<details>
  <summary><h3>🖥️ <strong>메인</strong></h3></summary>
  
  - ![메인 화면 1](https://drive.google.com/uc?id=1yh6VjIbCeInYo-_KqQyW2vTEP7gnNA-F)
  - ![메인 화면 2](https://drive.google.com/uc?id=1hEVSpboUQm9o5r213w3gJHWvmnzdczJ_)  
  
</details>




<details>
  <summary>👨‍💻<h3><strong>사용자</strong></h3></summary>
  
   ![사용자 화면 1](https://drive.google.com/uc?id=1O1BXu6WmtA2OyEG3nG2A9kEhjSuktFGa)  
   ![사용자 화면 2](https://drive.google.com/uc?id=1HJqOBN6oXwjIMtY-maCrsDgMHhYoI_E1)  
   ![사용자 화면 3](https://drive.google.com/uc?id=15bSdEFbeBru9B1uCSQVIPwmcM86crBPu)  
   ![사용자 화면 4](https://drive.google.com/uc?id=15c2rdAMuEmnWuePVZUbLWwCZBsyvlZTl)  
   ![사용자 화면 5](https://drive.google.com/uc?id=1clm5jBjPY96qctQZUH6FusEwS1XF_cHT)  
   ![사용자 화면 6](https://drive.google.com/uc?id=11ZOWSOEmw6deB-CA1sTSIDZ6xsCcjL77)  
   ![사용자 화면 7](https://drive.google.com/uc?id=1Royy_rLz6QXJB7fCIqL4phCMQf1iRFjD)  
   ![사용자 화면 8](https://drive.google.com/uc?id=1voKvWLdAeKPpy0MxVfqQbo-lr9iK-NYh)  
   ![사용자 화면 9](https://drive.google.com/uc?id=1pt-fA0FSDrgToliYUJ8xpbSVUdvPyIwF)  
   ![사용자 화면 10](https://drive.google.com/uc?id=1kB_HyRvQ0BACRceCA-hcf0pYr74aKniw)  
   ![사용자 화면 11](https://drive.google.com/uc?id=1J5M1lapb-Zpg_E1OkDHWdL9Plm1JYlzR)  
   ![사용자 화면 12](https://drive.google.com/uc?id=11kg9Bni5id0ywQ9KNXb1lOTtjZhgNCeO)  
  
</details>





<details>
    <summary><h3>🛒구매</h3></summary>
  
   ![구매 화면 1](https://drive.google.com/uc?id=1NzWO2TYP_oB4soSpc6yet-DMpefrdqVf)  
   ![구매 화면 2](https://drive.google.com/uc?id=1ihFTmX9HV5qs5a4d7FoaquHDbkcHL9Di)  
   ![구매 화면 3](https://drive.google.com/uc?id=1QVO1rzbdXg5uWn4FMdSMjCtzTKhf2phd)  
   ![구매 화면 4](https://drive.google.com/uc?id=14vNoq2OgDvmC8L0wHo2WecZ7hS5CZwuA)  
   ![구매 화면 5](https://drive.google.com/uc?id=1SrJGinIcJ_SrdQyjRskCUQgbP-vK7HyB)  
   ![구매 화면 6](https://drive.google.com/uc?id=1tWKuvCN7vdryQ_Lwj9x6QKPOACXOy5Hz)  
  
</details>



<details>
   <summary><h3>📝게시판</h3></summary>

  ![게시판 화면 1](https://drive.google.com/uc?id=1uO0LOAOjzWHgF0A5mxLrnHFIxeSXTS-9)  
  ![게시판 화면 2](https://drive.google.com/uc?id=1_kohsYXQ57KAEgcDht8_iUcm63uxQSvD)  
  ![게시판 화면 3](https://drive.google.com/uc?id=1JjJ9nTbHnipXefpZvB7IYKcC4SsOKw-m)  
  ![게시판 화면 4](https://drive.google.com/uc?id=1YqUDhQAAMJrfPLT2eddZouSxMJF62Z61)

</details>






<details>
  <summary><h3>🗓️운동계획표</h3></summary>

  ![운동계획표 화면](https://drive.google.com/uc?id=1i_Eu3jcmxAmLOztfJIER5MolzlshGXSJ)

</details>





<details>
  <summary><h3>🛠️<strong>관리자</strong></h3></summary>

  ![화면1](https://drive.google.com/uc?id=153Nywa1Jwo9pR3tkO9ioTGSDTAjWeT6f)  
  ![화면2](https://drive.google.com/uc?id=12fL2jq4lFESM7zK8d5Zrg0GUFNjCJKbM)  
  ![화면3](https://drive.google.com/uc?id=1Gr429NeFAUKxSkFhZn2vBj38eF-37mfd)  
  ![화면4](https://drive.google.com/uc?id=1-97K9z_EKkNg4AxKiVI7m63kUGmqIobD)  
  ![화면5](https://drive.google.com/uc?id=18MjR2CW3hBDcwUfaGe45ra_Jp66-dEm_)  
  ![화면6](https://drive.google.com/uc?id=1VJ-BciCK5u3FcUxIJy1KYCUXX2P_41eB)  
  ![화면7](https://drive.google.com/uc?id=1uuxEzLK7scoeSVOShpmy3J3yuJ63NRi1)  
  ![화면8](https://drive.google.com/uc?id=1VGsfryN3tQ96wbblTjeKhs9IyLZTEGRg)  
  ![화면9](https://drive.google.com/uc?id=1dfZvqbG9ueTYVmzVRbyAmXvDNHe_Joyp)  
  ![화면10](https://drive.google.com/uc?id=1dUwCd3wUYsj_5ndBZNVifgXOH5LdjWqv)  
  ![화면11](https://drive.google.com/uc?id=1m9Gcwv_4PrH3krgpaQk-5UaEqvrs6-Fc)  
  ![화면12](https://drive.google.com/uc?id=1NL6cHICa1-psjZ-YmkLcv9Pb9tI_RtKb)  
  ![화면13](https://drive.google.com/uc?id=1tNXqpTcewchG1zuWEIylpeuXeGjOVsxB)  

</details>



---
&nbsp;

# ✨📊 **실제 화면**

<details>
  <summary><h3>🖥️ <strong>메인</strong></h3></summary>
    
  ![메인 화면 1](https://drive.google.com/uc?id=1Uc68G_fKXEXpbpQwmw_ehMtj28TQcP8E)
  ![메인 화면 2](https://drive.google.com/uc?id=1Uo2AOU0S0dM2wE4NOvHmBgi7-4WmaeVt)
  ![메인 화면 3](https://drive.google.com/uc?id=1hSRDulnuxRf6r9kk7ylSZxzFKHRB786z)
  ![메인 화면 4](https://drive.google.com/uc?id=1Up9a7utmk008C51bCwTNk0_pb48Jv1id)
  
</details>

---

<details>
  <summary><h3>👨‍💻 <strong>사용자</strong></h3></summary>
    
  ![사용자 화면 1](https://drive.google.com/uc?id=1Vns8UHr9Czb7mCp0oRkMvdlziCZicLsb)
  ![사용자 화면 2](https://drive.google.com/uc?id=1gKsHrmqugAXwskpHHzOj2QhOeXQhdDNS)
  ![사용자 화면 3](https://drive.google.com/uc?id=1hTpezJdzQLhH3LDQCH-kPDpb6x81u74a)
  ![사용자 화면 4](https://drive.google.com/uc?id=1-AcOC5ooqzOqnshUxfqrcAs0YUFyUmvD)
  ![사용자 화면 5](https://drive.google.com/uc?id=1ja-sOvZ2j7p15DMnEtXviqiN_18NJiFO)
  ![사용자 화면 6](https://drive.google.com/uc?id=1rLu826EyHDDes2J4IM-6gAtZn4Cc6fnO)
  ![사용자 화면 7](https://drive.google.com/uc?id=121WbRNX12d6LvIDWxccaLHhtfDm-Uls_)
  ![사용자 화면 8](https://drive.google.com/uc?id=15MMalJR4fd_4Sw1fhrwTd9Slbw16W2Nb)
  ![사용자 화면 9](https://drive.google.com/uc?id=1uQtkwajZWYumxgvRC3jHBNLXscEqlHeo)
  ![사용자 화면 10](https://drive.google.com/uc?id=1ZvEBl78uv1MwJyduIHh-0K1Vk6SXxbLd)
  ![사용자 화면 11](https://drive.google.com/uc?id=1mtO7EgM51fYJFiVh_QgKi_wR7rVK3xrM)
  ![사용자 화면 12](https://drive.google.com/uc?id=1gI3UU8nHksHzgKc-NwUHKV531sbQYdz4)

</details>

---

<details>
  <summary><h3>🛒 <strong>구매</strong></h3></summary>
    
  ![구매 화면 1](https://drive.google.com/uc?export=view&id=1mfs0TBP-93EDxgPWtjHDm4CnJVeJubfB)
  ![구매 화면 2](https://drive.google.com/uc?export=view&id=18RUIJA9hgrSM4asnp4GHeVSeJUM5nU2U)
  ![구매 화면 3](https://drive.google.com/uc?export=view&id=1O1zKaSeBCMyvTAML6RTrIiW_SLpC9a0Z) 
  ![구매 화면 4](https://drive.google.com/uc?export=view&id=1Vg5ufkETUEam0LcLRuNLrD_yTwCPGmRk)
  ![구매 화면 5](https://drive.google.com/uc?export=view&id=1e2nNdmhYeJwS6UnuKpsi71-YPCO8GnGT)
</details>


---

<details>
 <summary><h3>📝 <strong>게시판</strong></h3></summary>
    
  ![게시판 화면 1](https://drive.google.com/uc?id=1lhLfroTuvEUKkrS40B0SRMAAIXFGQDxh)
  ![게시판 화면 2](https://drive.google.com/uc?id=1w7vIgGkxcYcaTNVFk99gEY_SWYGc5Cb_)
</details>

---

<details>
  <summary><h3>🗓️ <strong>운동계획표</strong></h3></summary>
    
  ![운동계획표 화면](https://drive.google.com/uc?id=1sO1FP1Lua8ykdPyNZTe1AYWVymS02IGD)
</details>

---

<details>
  - <summary><h3>🛠️ <strong>관리자</strong></h3></summary>
    
  ![관리자 화면 1](https://drive.google.com/uc?id=1B8LTUYdehlfvMRUd_AXhCsrNtRSCAxP0)
  ![관리자 화면 2](https://drive.google.com/uc?id=11yqmvEDOs5DemuaqLkJ0RhJ-JkmdvOAx)
  ![관리자 화면 3](https://drive.google.com/uc?id=1gcoGjZpWV_wkz-ICyLhzw0Y9tHmcPOeP)
  ![관리자 화면 4](https://drive.google.com/uc?id=1wtZrhqDV9H6h6NplAFcTzQ8YPuzwYTKl)
  ![관리자 화면 5](https://drive.google.com/uc?id=1773uAE71llv-bJMFk-D1brLXNzU6U_ez)
  ![관리자 화면 6](https://drive.google.com/uc?id=1pjCkvkHeufRn-x5q0Bw39DPuT_83-0yX)
  ![관리자 화면 7](https://drive.google.com/uc?id=1gRzloprNVjySX3Ec0ZQm-fFzWgoKt9N8)
  ![관리자 화면 8](https://drive.google.com/uc?id=14XyRjNqg1T7f7kY1ZfO8JKdwCuqIGOdj)
  ![관리자 화면 9](https://drive.google.com/uc?id=1Dfd6QNfg9ZojGtGAkNB9r0D4V3bkWBTN)
  ![관리자 화면 10](https://drive.google.com/uc?id=1JhYmLXcIyMLIJhVfyU7UqtgbpuYWDFan)
  ![관리자 화면 11](https://drive.google.com/uc?id=1IKwCA9CU7cHNaaULMDOWbQ2KHbLP3AiX)
</details>

---



&nbsp;
# 🎯 **주요 기능**
## ✅ 회원가입 및 로그인/로그아웃  
## ✅ 실시간 헬스장 이용자 수 확인  
## ✅ QR코드 기반 출입 관리  
## ✅ PT 예약 및 트레이너 스케줄 관리  
## ✅ 회원 정보 수정 및 권한 관리  
## ✅ 관리자 페이지를 통한 회원 및 예약 관리  
## ✅ 이용 통계 제공  

---


&nbsp;
<h2>📝 <strong>개별 평가</strong></h2>

## 김도현
- **한계점**: 프로젝트를 진행하면서 스크립트 및 API에 대한 이해도가 많이 부족하다는 것을 느꼈고 이로 인해 구현하고 싶은 기능들은 많았지만 제대로 구현하지 못해 아쉬웠던 것 같습니다.
- **보완점**: 추후 스크립트와 API를 활용할 때 익숙치 않은 부분들에 대해 더욱 다양한 코드를 작성하며 적응해가야 할 것 같습니다.
- **소감**: 이번 프로젝트는 이전 미니 프로젝트에서 얻은 경험을 바탕으로 주제 선정에서부터 팀원들과 의견을 나누며 구상을 탄탄히 다졌고, 이를 통해 프로젝트 목표를 명확히 설정하고 진행하게 되었습니다. 하지만 개발 과정을 진행하면서 수정 사항이 생길 수밖에 없다는 점을 다시 한 번 깨닫게 되었습니다. 그리고 개발 과정에서 팀원들 간 활발한 의사소통으로 각자 잘 모르는 부분을 함께 공유하고 고민하여 안 되던 기능을 하나씩 구현하는 성취감을 느낄 수 있었던 값진 경험을 하게 된 것 같습니다.



