# musinsa-price-tracker
카카오클라우드스쿨 3기 미니프로젝트 무신사 스탠다드 가격 추적 사이트

## 개발 동기

```
- 이 프로젝트는 사용자들에게 무신사 스탠다드 제품의 가격 변동 추적과 알림 기능을 제공하여 효율적인 쇼핑을 돕고자 합니다.
- 사용자들은 더 이상 수동으로 가격 변동을 주시하지 않아도 되며, 가격이 원하는 범위에 도달하면 즉시 알림을 받을 수 있습니다.
- 이를 통해 시간을 절약하고 가격 경쟁력 있는 제품을 놓치지 않을 수 있습니다

```

## 주요기능

```
1. 외부 인증 기능:
  - 사용자는 구글, 네이버, 카카오 계정을 활용하여 간편하게 계정을 생성하고 로그인할 수 있습니다.

2. 제품 정보 수집 및 저장:
  - 무신사 스탠다드 제품의 정보를 웹 스크래핑을 통해 수집하고 데이터베이스(AWS RDS)에 저장합니다.

3. 제품 모니터링 및 추적:
  - 사용자는 특정 제품을 선택하여 가격 변동을 실시간으로 모니터링하고 추적할 수 있습니다.

4. 이메일 기반 가격 변동 알림:
  -사용자가 설정한 가격 이하로 제품 가격이 하락하면 등록된 이메일 주소로 알림 이메일을 보냅니다.

5. RESTful API 서버 구축:
  - 사용자 관리, 제품 정보 제공, 가격 변동 알림 설정과 같은 기능을 제공하는 RESTful API 서버를 구축합니다.

6.데이터 시각화:
  - 사용자들에게 무신사 스탠다드 제품의 가격 변동 추세를 그래프와 차트로 시각화하여 제공합니다.
```

## 구조
**![](https://lh4.googleusercontent.com/TRn7N4W8YuHTSttwzZJCQmmJX97Op2mETQEdAqiGoS11WXXxhA6VSgpYByBXjagNPwMOsb2vRBvP8iWXzDBtsx4ksYG2tStLXQ8PNXz_4tA-A-U0DYGUUnsminpCPjdfCgeW000CGjABKRt2Z3VVkJhF4g=s2048)**

## 사용자 UI

### 메인 화면 (상품 리스트)
**![메인화면](https://lh6.googleusercontent.com/re9jALIPPt4REm1O-3u8Sq6VER_P7j8brx2pOspJkVedI4UiRB6WQIRgVqeyrODPjx7VSoFmIhwu62kcy3HOq80XQjzSO8VeFpP0WQFV6otVbdbUjYc9X69bk2_V26EBpFJr8qF9ekWkUggIadNjrzhwaw=s2048)**

### 소셜 로그인 (외부 인증)
**![](https://lh5.googleusercontent.com/CMjFtaX4TaYXJeYZj1AAP40ewpuaqYr5GmmzcV4U-aaPtaHRo6NTaC0g5-dAVO_bZzbBdte40sbjcEjzHm65nL9qhCazqDFZCUwbOS_KOPyQCCDbS72kKMPdOY-oPq1KC1T-4mKJGqydyLcfryIq8Pd_GA=s2048)**

### 상품 상세페이지 (가격 차트)
**![](https://lh6.googleusercontent.com/z0tFZzypr3Dr_846Uk7Q2KiLvI3exAG0ztGBj0J1m66gxzUj2G79348xDTehq_KFVTzaSBkYuPoUddRHjOk_Rgqzw-_XZJivHHOcpYlot4iFqKAD-z7kHxeVdFgfD9w2TkUMiBxhEezhVLRC3k4wmbHJBQ=s2048)**

## 가격 알림 설정
**![](https://lh3.googleusercontent.com/Frybs2EL_4KDo5WJAGL6BiaPjWDyy7zSfk4MkZ55qd1QAAGYib2Oa6qkmVs1jYfDA8drt7uptOpxtVv0B5oscBQyViaYn5KAekkdMj_PZpW4UivK66gb_9ptmFRChN7Hp5mI_3LF0yvM9ZT-o6yxsX_rdA=s2048)**

## 알림 이메일 예시
<img width="1437" alt="스크린샷 2023-08-17 오전 12 08 21" src="https://github.com/musinsa-price-tracker/musinsa-price-tracker/assets/77106988/db4c1df5-0d3f-4156-ae90-2bbe9503e99e">




## 활용 기술

- Language - Java, Python3, Javascript, HTML/CSS
- Framework: Spring Boot
- etc: Docker, AWS

