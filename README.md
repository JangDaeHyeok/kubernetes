# kubernetes
쿠버네티스 관련 repository

1. jenkins
- 젠킨스 pod 배포 관련 yaml


2. monitoring
- 쿠버네티스 클라우드 모니터링 관련 pod 배포를 위한 yaml
- 프로메테우스, node-exporter, grafane
- role 설정, service 설정


3. sonarqube
- 프로젝트 배포 시 품질 체크를 위한 소나큐브 pod 배포 yaml
- sonarqube, postgres 관련


4. toy_project
- 토이프로젝트 pod 배포 관련 yaml
- CI(jenkins) 배포를 위한 Jenkinsfile
- docker hub image 사용을 위한 Dockerfile
- pod, deployment, service
- pv, pvc (nfs 사용)
- tomcat, nodejs 환경
- board 프로젝트는 k8s service에서 LoadBalancer 사용
