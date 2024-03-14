# Infrastructure

![image](https://github.com/dhowl1/Infrastructure/assets/139436754/a2a02b54-08c2-4eed-ad16-761894db4bb5)

구성 요소
MongoDB Deployment: MongoDB 데이터베이스를 실행하는 Kubernetes Deployment. 데이터 지속성을 위한 PersistentVolumeClaim을 사용합니다.
Prometheus Deployment: 시스템 및 서비스 모니터링을 위한 Prometheus 서버를 실행하는 Kubernetes Deployment.
Grafana Deployment: Prometheus에서 수집한 데이터를 시각화하기 위한 Grafana 서버를 실행하는 Kubernetes Deployment를 구현하였습니다.
