# Infrastructure

![image](https://github.com/dhowl1/Infrastructure/assets/139436754/a2a02b54-08c2-4eed-ad16-761894db4bb5)

이 프로젝트는 Flask를 사용하여 만든 웹 애플리케이션으로, MongoDB, Kubernetes 클러스터, Docker 엔진의 연결 상태를 확인하는 Health Check API를 제공합니다. `/health` 엔드포인트를 통해 각 컴포넌트의 상태를 JSON 형태로 반환합니다.

이 앱은 `http://localhost:8080`에서 실행됩니다. `PORT` 환경 변수를 설정하여 다른 포트에서 실행할 수도 있습니다.
/health` 엔드포인트에 GET 요청을 보내면, MongoDB, Kubernetes 클러스터, Docker 엔진의 연결 상태를 확인하고 그 결과를 JSON 형태로 반환합니다.
status는 모든 체크가 성공하면 "up", 실패하면 "down"입니다.
