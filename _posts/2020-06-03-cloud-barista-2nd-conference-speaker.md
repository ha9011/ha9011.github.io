---
layout: post
title: GABOM 프로젝트 
subtitle: 여행, 채팅 등 복합적 여행 플렛폼
cover-img: ../assets/img/gabom/gabom.JPG
tags: [Spring, java, Project]
---


## 스프링으로 웹구현한 GABOM 프로젝트 입니다.
- 4인(하동원 - 조장, 이예상, 김성준, 마재환)
- 전반적인 아이디어, DB 설계, 비지니스로직 구현 등 포괄적인 업무를 담당 했습니다.

## 작품명과 소개
- GABOM (여행을 떠나다)
- 단순 예약이 아닌, 여행계획을 공유하고 숙박, 음식 그리고 SNS, 소모임 까지 할 수 있도록 구현한 복합 여행 플렛폼
- 담당 분야 : 소모임, 예약, 여행 공유 API 지도 구현, 공공데이터 API(여행장소), 채팅 등 구현




<br><br><br>
# 메인페이지ㅎㅎ
|||
| ------------------------------ | :----------------------------------: |
|  사진 |   <img src="../assets/img/gabom/main1.JPG" width="30%">   <img src="../assets/img/gabom/main2.JPG" width="30%"> <img src="../assets/img/gabom/main3.JPG" width="30%">|
|  내용 |    - Main page 입니다. -첫번째 사진은 메뉴들이 있고,<br> -두번째 사진엔 인기있는 여행계획 순위입니다. <br>-세번째는 최근 예약한 숙소,음식점 입니다.|

<br><br><br>
# 숙박 page 1 - 호스트가 운영자에게 등록된 집
|||
| ------------------------------ | :----------------------------------: |
|  사진 |    <img src="../assets/img/gabom/house1_1.JPG" width="900px"> <hr> <img src="../assets/img/gabom/house1_2.JPG" width="900px"> <hr> <img src="../assets/img/gabom/house1_3.JPG" width="900px">|
|  내용 |    - 첫번째, 숙박 가능한 숙소들 리스트 <br> - 두번째, 원하는 숙소 클릭 후 예약모습(기존에 예약된 날짜는 disable 처리) <br> - 세번째, 숙박한 사람들의 리뷰나 comment 모습|
|  사진 |   <img src="../assets/img/gabom/house1_4.JPG" width="900px"> <hr> <img src="../assets/img/gabom/house1_5.JPG" width="900px">|
|  내용 |   - 첫번째, 지역을 검색합니다 <br> - 검색된 지역에 대한 숙소 리스트와 지도안에 마커로 표시했고, 마커에 포인트를 올리면 해당 숙소에 대한 사진이 나옵니다 |

<br><br><br>
# 숙박 page 2 - 현 플렛폼에 원하는 숙소가 없을 경우, 크롤러를 통해 호텔스컴바인에서 원하는 숙소 데이터를 가져옴
|||
| ------------------------------ | :----------------------------------: |
|  사진 |   <img src="../assets/img/gabom/house2_1.JPG" width="900px"> <hr>   <img src="../assets/img/gabom/house2_2.JPG" width="900px%"> |
|  내용 |    - 첫번째, 지역과 날짜를 검색할 경우, 크롤러를 통해 호텔스컴바인의 데이터를 가져왔습니다..<br> -두번째, 숙소 클릭시, 호텔스컴바인 홈페이지로 이동하게 됩니다.|

<br><br><br>
# 맛집 - 숙박과 동일한 형태입니다.
|||
| ------------------------------ | :----------------------------------: |
|  사진 |   <img src="../assets/img/gabom/food1.JPG" width="900px"> <hr>   <img src="../assets/img/gabom/food2.JPG" width="900px%"> |
|  내용 |    - 첫번째, 숙소가능한 리스트 <br> -두번째, 예약과 리뷰|

<br><br><br>
# 소모임 plot. 1 첫화면
|||
| ------------------------------ | :----------------------------------: |
|  사진 |   <img src="../assets/img/gabom/somoim_main_1.JPG" width="45%"> <hr>   <img src="../assets/img/gabom/somoim_main_2.JPG" width="45%"> |
|  내용 |    - 첫번째, 검색과 소모임 만들 수 있습니다. <br> -두번째, 가입한 소모임 리스트 입니다.|

<br><br><br>
# 소모임 plot. 2 정모
|||
| ------------------------------ | :----------------------------------: |
|  사진 |   <img src="../assets/img/gabom/jungmo_1.JPG" width="900px"> |
|  내용 |    소모임 첫화면입니다, 방장은 정모를 만들 수 있으며, <br> 만들어진 정모에 내용과 참석 여부, 참석자 명단을 볼 수 있습니다.|
|  사진 |   <img src="../assets/img/gabom/jungmo_2.JPG" height="300px" width="30%">  <img src="../assets/img/gabom/jungmo_3.JPG" height="300px" width="30%"> <img src="../assets/img/gabom/jungmo_4.JPG" height="300px" width="30%"> |
|  내용 |    - 첫번째, 정모를 만들기 위한 form 이며 지도API도 구현. <br> -두번째, 만들어진 정모에 대한 내용을 보는 화면. <br> -세번째, 참석자 리스트.|

<br><br><br>
# 소모임 plot. 3 게시판 & 앨범
- 게시판과 앨범은 비슷해서 게시판만 보여드리겠습니다.

|||
| ------------------------------ | :----------------------------------: |
|  사진 |   <img src="../assets/img/gabom/somoim_board_1.JPG" width="33%" height="250px"> <img src="../assets/img/gabom/somoim_board_2.JPG" width="33%"> <img src="../assets/img/gabom/somoim_board_3.JPG" width="33%" > |
|  내용 |    -첫번째, 게시판 리스트 입니다. <br> -두번째, 게시판 작성 form <br> -세번째, 해당 게시글에 대하여 좋아요, 댓글, 댓글 페이징 구현 |

<br><br><br>
# 소모임 plot. 4 채팅


|||
| ------------------------------ | :----------------------------------: |
|  사진 |   <img src="../assets/img/gabom/chatting_1.gif" width="900px" height="250px">  |
|  내용 |    -첫번째, 채팅 GIF 입니다. 스크롤올리면 예전 채팅데이터를 가져오도록 구현했고, 그 채팅데이터의 날짜도 볼수 있게 끔 구현했습니다 |


<br><br><br>
# 소모임 plot. 5 알람


|||
| ------------------------------ | :----------------------------------: |
|  사진 |   <img src="../assets/img/gabom/somoim_a_1.JPG" width="45%" > <img src="../assets/img/gabom/somoim_a_2.JPG" width="45%">  |
|  내용 |    -첫번째 사진에서 정모게시판을 만들면, <br> -두번째 사진에서 처럼, 정모 맴버들에게 알림이 가게됩니다. <br> 알람 클릭시 해당 소모임으로 이동하게 됩니다.|



<br><br><br>
# 여행 plot. 1 메인


|||
| ------------------------------ | :----------------------------------: |
|  사진 |   <img src="../assets/img/gabom/trip_main_0.JPG" width="900px" >   |
|  내용 |    -여향계획을 만들거나, 추천여행보기에서 여행을 검색해서 저장 할 수 있습니다.|

|||||
| ------------------------------ | :----------------------------------: |:----------------------------------: |:----------------------------------: |
|  사진 |   <img src="../assets/img/gabom/trip_main_1.JPG" width="100%" > | <img src="../assets/img/gabom/trip_main_2.JPG" width="100%" > | <img src="../assets/img/gabom/trip_main_3.JPG" width="100%" >  |
|  내용 |    -여행 메인사진 상단에 [내여행]이라는 메뉴를 누를 경우 나타납니다.<br> - 같은 여행 맴버, 초대, 날짜 변경, 여행계획 삭제가 있습니다 |   -여행 계획 초대시, 초대된 사람은 알람창이 뜨고 클릭하면 여행페이지로 이동됩니다 |   - 좌측 메뉴에 요청 받은 계획에 승인, 거절을 할 수 있습니다. |






| 사진 |                                    내용                                            |
| ------------------------------ | :----------------------------------: |
|<img src="../assets/img/pythonProject1/python_R_page-0001.jpg" width="30%"> | 강동재<BR>커뮤니티 리더  [[SlideShare](https://www.slideshare.net/cloud-barista/cloudbarista-2-cloudbarista-2st-open-seminar-cloudbarista-technology-and-open-source-community-235056632)] [[GitHub](https://github.com/cloud-barista/docs/blob/master/openseminar/v0.2.0-cappuccino/ppt_files/Cappuccino-OpenSeminar-1-Cloud-Barista%20Technology%20and%20Open%20Source%20Community.pdf)] [[YouTube](https://youtu.be/_cwAZsIAWjg)] |
| CB-Spider : 전세계 클라우드를 엮는 그날까지<BR>(멀티 클라우드 인프라 연동) | 김병섭 CB-Spider<BR>프레임워크 리더 | [[SlideShare](https://www.slideshare.net/cloud-barista/cloudbarista-2-interworking-with-multicloud-infrastructure-235058344)] [[GitHub](https://github.com/cloud-barista/docs/blob/master/openseminar/v0.2.0-cappuccino/ppt_files/Cappuccino-OpenSeminar-2-CB-Spider-Interworking%20with%20multi-cloud%20infrastructure.pdf)] | [[YouTube](https://youtu.be/qjflPwN_Y-M)] |
| Coffee Break |||
| **CB-Tumblebug : 최적 멀티 클라우드 인프라를 찾아서**<BR>(멀티 클라우드 인프라 통합 운용 관리) | **손석호**<BR>**CB-Tumblebug 프레임워크 리더** | [[SlideShare](https://www.slideshare.net/cloud-barista/cloudbarista-2-multicloud-infrastructure-integrated-operation-management)] [[GitHub](https://github.com/cloud-barista/docs/blob/master/openseminar/v0.2.0-cappuccino/ppt_files/Cappuccino-OpenSeminar-3-CB-Tumblebug-Multi-cloud%20infrastructure%20integrated%20operation%20management.pdf)] | [[YouTube](https://youtu.be/qxEnboezCFg)] |
| CB-Ladybug : 애플리케이션을 전세계 곳곳으로<BR>(멀티 클라우드 애플리케이션 통합 운용 관리) | 김수영 CB-Ladybug<BR>프레임워크 리더) | [[SlideShare](https://www.slideshare.net/cloud-barista/cloudbarista-2-integrated-management-of-multicloud-applications)] [[GitHub](https://github.com/cloud-barista/docs/blob/master/openseminar/v0.2.0-cappuccino/ppt_files/Cappuccino-OpenSeminar-4-CB-Ladybug-Integrated%20management%20of%20multi-cloud%20applications.pdf)] | [[YouTube](https://youtu.be/mCdNDBouiEU)] |
| Coffee Break |||
| CB-Dragonfly : 전세계 클라우드가 다보여<BR>(대규모 멀티 클라우드 모니터링) | 권경민 CB-Dragonfly<BR>프레임워크 리더 | [[SlideShare](https://www.slideshare.net/cloud-barista/cloudbarista-2-cbdragonfly-multi-cloud-integration-monitoring-framework)] [[GitHub](https://github.com/cloud-barista/docs/blob/master/openseminar/v0.2.0-cappuccino/ppt_files/Cappuccino-OpenSeminar-5-CB-Dragonfly-Multi%20Cloud%20Integration%20Monitoring%20Framework.pdf)] | [[YouTube](https://youtu.be/WktcVBTbVfw)] |
| CB-Waterstrider : 멀티 클라우드와 스킨십을<BR>(멀티 클라우드 서비스 공통 플랫폼 웹도구) | 정영태 CB-Waterstrider<BR>프레임워크 리더 | [[SlideShare](https://www.slideshare.net/cloud-barista/cloudbarista-2-cbwaterstrider-multi-cloud-service-common-framework-webtool)] [[GitHub](https://github.com/cloud-barista/docs/blob/master/openseminar/v0.2.0-cappuccino/ppt_files/Cappuccino-OpenSeminar-6-CB-Waterstrider-Multi%20Cloud%20Service%20Common%20Framework%20WebTool.pdf)] | [[YouTube](https://youtu.be/-lUhCizLs-A)] |
| CB-Bridge : 원 클릭으로 Cloud-Barista 운용하기<BR>(Cloud-Barista 운용 관리) | 서지훈 CB-Bridge<BR>프레임워크 리더 | [[SlideShare](https://www.slideshare.net/cloud-barista/cloudbarista-2-cbbridge-multicloud-common-platform-operation-management)] [[GitHub](https://www.slideshare.net/cloud-barista/cloudbarista-2-cbbridge-multicloud-common-platform-operation-management)] | [[YouTube](https://youtu.be/aVeQ-PUWwq4)] |

<br/>

### 컨퍼런스 질의 사항 답변서(Q&A)

* [질의 사항 답변서 다운로드](https://github.com/cloud-barista/docs/blob/master/openseminar/v0.2.0-cappuccino/Cloud-Barista_2nd_Open_Conference-%EC%A7%88%EC%9D%98%EC%82%AC%ED%95%AD_%EB%8B%B5%EB%B3%80%EC%84%9C.pdf "https://github.com/cloud-barista/docs/blob/master/openseminar/v0.2.0-cappuccino/Cloud-Barista_2nd_Open_Conference-%EC%A7%88%EC%9D%98%EC%82%AC%ED%95%AD_%EB%8B%B5%EB%B3%80%EC%84%9C.pdf")


### Cloud-Barista 소스 코드 및 설치 가이드

* [v0.2.0-cappuccino 소스 코드 및 설치 가이드](https://github.com/cloud-barista/cloud-barista/tree/v0.2.0-cappuccino "https://github.com/cloud-barista/cloud-barista/tree/v0.2.0-cappuccino")
