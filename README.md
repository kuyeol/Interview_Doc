# Interview_Doc



## 개인 개발 환경

윈도우 노트북1대
리눅스 노트북1대
DevZero(클라우드 컨테이너)

GCP도 이용하여 실습중 무료 리소스의 자원 관리 한정된 시간 등의 문제로 구형 노트북에
리눅스 설치 후 공유기IP 설정으로 외부 접속 가능하도록 개방하고 
Iptables 규칙에 도커(docker0) 네트워크를 개방IP 연결 추가해서
리모트 컨테이너(keycloak,postgres,kafka,minio,elastick...) 사용하고 있습니다

리눅스PC에서 도커로 이용중인 컨테이너 수가 많아짐으로 인해 셧다운 이슈로
분산 개발 필요가 생겨 고민하던 중 별도의 결제 요구 없이 이용 가능한
DevZero 클라우드 서비스를 알게 되어 이용중 입니다

IDE는 자바 프로젝트에서 인텔리제이(EAP)를 사용하고 
간단한 코드 수정과 원격 레포 확인 및 프론트 작업에는 VSCODE 사용 하고있습니다



# 언어

#### Java 
#### SQL
#### TypeScript
#### HTML,CSS
#### Bash

# 프레임워크

#### Quarkus
#### Spring
#### Angular
#### JPA

# 사용툴

  
### docker

- 모니터링 및 리소스 설정
- yml 파일 작성 후 컴포즈 실행
  - 빌드 환경 정의 [`컨테이너명`,`커맨드`,`어드민`,`포트`,`네트워크`,`볼륨에서 파일 링크` ..]
  
### docker-cli

- 리모트 사용 시 컨테이너 내부 접속
- 컨테이너 상태 확인, 컨테이너 실행 중지 삭제 컴포즈 업 등...
- 내부 컨테이너 접속 후 스크립트 사용
  - (psql 테이블 생성,조회,업데이트 / kafka 토픽 생성)
  
### vim

- 리모트 터미널 접속 시 파일 수정 저장 생성
- `vim . ` 이용하여 터미널에서 폴더 및 파일 탐색
  
### github

- 저장소 이용 하여 코드 관리
- 예제 코드 저장 시 클론 포크 등..
- 코드 정리 용도로 사용하기 위해 프론트페이지를 워크플로 이용하여 배포
  - 진행중인 코드 작성 및 실습 시간 외 작업이 소요되어 작업중인 레포지토리 내부에 마크다운 이용하여 정리
- 프론트엔드 워크플로에 트리거 구성하여 푸시 명령 시 빌드 이벤트 발생 구성
- git 커맨드 이용하여 클론, 커밋, 푸시, 용  









