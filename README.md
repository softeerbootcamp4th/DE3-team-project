# 현대자동차 소프티어 부트캠프 4기 Data Engineering 3조

## 팀원 소개

| 곽범규                                          | 이구                                       | 최우형                                  |
|----------------------------------------------|------------------------------------------|--------------------------------------|
| DE                                           | DE                                       | DE                                   |
| [@nothingmin](https://github.com/nothingmin) | [@99sphere](https://github.com/99sphere) | [@dn7638](https://github.com/dn7638) | 

## 폴더 구조

- `model/`: 알람을 받을 기준이 되는 모델을 개발하는 과정과 결과를 정리해 놓은 폴더
- `infra/`: 데이터 파이프라인 인프라를 코드로 정의한 파일들이 포함된 폴더.

**자세한 설명은 폴더 별로 README가 작성되어 있습니다.**

# 아키텍처

![cloudformation.drawio.png](/infra/cloudformation.drawio.png)
라우팅 테이블과 AWS SecretManager VPC Endpoint는 생략