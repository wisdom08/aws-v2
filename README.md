# aws-v2

## Springboot 2.7.3, JDK 11
- devtools
- springweb
- lombok

## 배포 위치 
- EC2

## 배포 방법
- 로컬에서 github 업로드
- EC2에서 github 다운로드
- 프로젝트 테스트
- 프로젝트 빌드
- nohub 으로 백그라운드 실행
- 오류 로그 남기기 (표준 입출력 리다이렉션)
- 서버가 종료되면 cron으로 자동 재시작


## 재배포 방법
- 개발환경(집 컴퓨터)에서 github 업로드
- 프로덕션(EC2)에서 deploy.sh 파일 실행

```
var.sh 파일 수정 후 다시 배포
(1) 버전
(2) 프로젝트 이름
```
