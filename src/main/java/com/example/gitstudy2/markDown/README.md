# 소개. Blog Service

------------------------------

- 블로그 검색과 관련된 서비스를 제공합니다.

# 빌드 결과물 

----------------------------------------

- [결과물 다운로드](https://www.google.com)

# 환경 소개

---------------------------------

- JAVA17
- SpringBoot 2.7.3
- ...

# module-application 

 ---

- 도메인 엔티티, 입력 포트, ...
  - `domain`
  - `service`
  - `port/input`


### 사용 

> `$ http GET http:localhost:8080/api/v1/blogs?keyword=SpringFramework`


### 요청

Parameter

| Name    | Type    | Description | Required  |
|---------|---------|-------|-----------|
| keyword | String  | 검색 키워드| 0         |
 | url     |  String | 블로그 url| X         | 

