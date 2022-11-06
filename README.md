# 팀명 A+2B+C = 100

## 팀원

이중곤(팀장-웹 백엔드)  
양찬영(웹 프론트 엔드)  
최재학(웹 백엔드)

### [졸업 작품 소개]
* 작품명
  Metroinder
* 개발환경
    + Frontend   
      <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
      <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white">
      <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">

    + Backend    
      <img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white">
      <img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">

    + DB  
      <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
* 작품 소개  
  지하철 정보 제공 맵 웹
* 작품의 특징  
  지하철의 혼잡도 정보와 가장 빠르게 이동할수 있는 경로를 알려주는 웹 사이트 입니다  
  공공데이터 API를 활용하여 혼잡도 정보와 자체 알고리즘을 사용하여 사람이적고 가장 빠르게 갈 수 있는 경로를 추천 해줍니다.
## [개발일지]
### [2022-11-02]
DB구조 설계 및 날씨정보 API 서칭

2022-11-05 회의

디자인 

다음주까지 디자인 토대로 기본 HTML/CSS 틀 작성

프론트 엔드

지하철 호선별 데이터 정리

백엔드

DB 재정리 ERD작성

날씨 API 선정후 작업 예정

### [2022-10-26]
지하철 실시간 정보 API 데이터 변환 방식 변경 및 리팩터링
### [2022-10-19]
유저 시나리오 작성 완료 및 추가 가능한 API서칭

2022-10-22 회의

프론트에서 카카오 맵 api를 이용해 역별로 포함하고 있는 호선 Json배열로 정리해서 백엔드에 전송
디자인 추가 작업
로그인 기능 추가 작업
GPS 설정 기능 추가 작업

### [2022-10-12]
포스터 추가 작업  
파워포인트 동영상 녹화  
실시간 API 데이터 타입 수정 및 디버깅
### [2022-10-05]
ppt작성
  + 정리한 자료 토대로 작성
  
  + 목차
    + 구성원 소개
    + 프로젝트 개요
    + 프로젝트 상세 및 시연
    + 개발 프로세스
  
유저 시나리오 작성
  + 로그인 
  + 비로그인시 접근 범위
  
2022-10-07 회의기록

디자인
훈련소 2주

프론트 엔드

노선도 정리 완료 및 백엔드 와 데이터 통신 테스트

백엔드

위도,경도,혼잡도,자체데이터 정리 하는 코드 작성중
위의 코드를 사용하여 길찾기 알고리즘 작성 테스트 중

### [2022-09-28]
DB데이터 양의 증가로 무료로 사용이 가능한 외부 DB서버 확인결과   
무료 DB서버는 없으나 GCP가 90일 무료 사용이 가능하고 회의때 결론 짓기
  
Power Point 자료 작성중

유저 시나리오 작성중

2022-10-01 회의기록

데이터 처리에 속도가 걸려서 Nosql 기반 DB로 차후 변경으로 결정

DB서버에 올리는건 서비스 실행 전으로 변경

디자인
훈련소 3주남음


프론트

역별 노선도 데이터 정리
버그 픽스중


백엔드

길찾기 알고리즘 cost에 위도 경도를 넣고 테스트 중 프론트 테스트를 할수가 없어 
서버에서만 데이터 확인


### [2022-09-21]
* 지하철 지연 정보 실시간 API테스트 결과 요청이 리퀘스트가 안됨  
사용할지 말 것인지 회의때 검토가 필요해 보임
* 실시간 지하철 위치 정보 API 데이터 필요한 JSON형태로 재가공 후 front에서 test


2022-09-24 회의기록

실시간 지연정보 API 사용 불가로 사용x

DB데이터 양의 증가로 무료로 사용이 가능한
외부 DB확인 해보기

기능 재 정리 및 유저시나리오 작성하기

디자인

공익훈련소 4주 입영

프론트

개인사유로 미참여

백엔드

길찾기 알고리즘 작업
* 평균값 33만을 기준으로 백분율로 산정을 하여 혼잡도 비율 cost 산정중
* 최단거리 산정값도 백분율 기준으로 cost 설정
* A*알고리즘 최단 거리 10순위 선정해서 사용자에게 보여줄 길찾기 경로 산정

### [2022-09-14]
손실된 작업 재 작성중

### [2022-09-07]
~~실시간 열차위치 API 데이터 사용 목적에 맞게 변경~~     
~~실시간 지연정보 데이터 확인~~   
노트북 SSD고장으로 인해 작업 손실
