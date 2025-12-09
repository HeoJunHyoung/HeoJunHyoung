<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:8E2DE2,100:4A00E0&height=220&section=header&text=Heo%20Jun%20Hyoung&fontSize=40&fontColor=FFFFFF&desc=Backend%20%26%20DevOps%20Engineer&descSize=20&animation=fadeIn" />
</div>

<br/>

### 🧑‍💻 About Me
> **"확장 가능한 아키텍처와 대용량 트래픽 처리에 집중하는 백엔드 개발자입니다."**

안정적인 서비스 운영을 위한 **MSA(Microservices Architecture)** 설계와 **시스템 성능 최적화**에 깊은 관심을 가지고 연구합니다.
비즈니스 요구사항을 기술적으로 해결하는 과정에서 발생하는 트레이드오프를 분석하고, 데이터 기반의 의사결정을 지향합니다.

* **Architecture**: Spring Cloud 기반의 MSA 구축, Kafka를 활용한 EDA(Event-Driven Architecture) 설계
* **DevOps**: On-Premise Kubernetes 클러스터 구축 및 운영, ArgoCD 기반의 GitOps 파이프라인 구현
* **Optimization**: 대용량 트래픽 처리를 위한 DB 인덱스 튜닝, Redis Caching 전략 수립 (Split Caching, Global Caching)

<br/>

---

### 🛠️ Tech Stack

#### **Backend**
![Java](https://img.shields.io/badge/Java-17-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.5.x-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Cloud](https://img.shields.io/badge/Spring%20Cloud-2025.0.0-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![QueryDSL](https://img.shields.io/badge/QueryDSL-5.1.0-007396?style=for-the-badge)

#### **Infrastructure & DevOps**
![Kubernetes](https://img.shields.io/badge/Kubernetes-On--Premise-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-GitOps-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-CI-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-22.04%20LTS-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)

#### **Data & Messaging**
![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-6.0+-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-Caching-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-CDC-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)

#### **Testing & Monitoring**
![k6](https://img.shields.io/badge/k6-Load%20Testing-7D64FF?style=for-the-badge&logo=k6&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

<br/>

---

### 🚀 Featured Project

#### [🔗 LinkFolio: 개발자 포트폴리오 공유 및 채용 플랫폼](https://github.com/HeoJunHyoung/Linkfolio-backend)
> **마이크로서비스 아키텍처(MSA) 기반의 대용량 트래픽 처리 시스템**

| 주요 기능 | 기술적 특징 및 해결 과제 |
| :--- | :--- |
| **하이브리드 인프라** | • VirtualBox VM 기반 **On-Premise Kubernetes 3-Node 클러스터** 직접 구축<br>• 외부 메시징 인프라(Kafka VM)와 K8s 클러스터를 분리한 **Hybrid Cloud Topology** 설계 |
| **데이터 동기화** | • **Kafka & Debezium(CDC)** 을 활용한 서비스 간 데이터 실시간 동기화<br>• **Transactional Outbox Pattern**을 적용하여 분산 환경에서의 데이터 정합성 보장 (SAGA Pattern) |
| **고성능 검색/조회** | • **Split Caching Strategy**: 정적 데이터(본문)와 동적 데이터(조회수)의 캐싱 라이프사이클 분리<br>• **Redis Write-Back**: 조회수 등 빈번한 업데이트를 메모리에서 처리 후 배치 동기화 (DB Lock 해소) |
| **실시간 채팅** | • **WebSocket + STOMP + Redis Pub/Sub** 아키텍처로 다중 서버 환경에서의 메시지 브로드캐스팅 구현<br>• **MongoDB**를 활용한 대용량 채팅 로그 저장 및 조회 최적화 |
| **성능 최적화** | • **k6 부하 테스트**를 통한 병목 구간 식별 및 튜닝 (조회 성능 73% 개선)<br>• 쿼리 실행 계획 분석을 통한 **복합 인덱스(Composite Index)** 적용 및 Full Table Scan 제거 |

<br/>

---

### 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=heojunhyoung&show_icons=true&theme=gruvbox&count_private=true" height="150" alt="stats graph" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=heojunhyoung&layout=compact&theme=gruvbox&hide=html,css" height="150" alt="languages graph" />
</div>

<br/>

---

### 📫 Contact
<a href="mailto:gjwnsgud4016@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://receiver40.tistory.com"><img src="https://img.shields.io/badge/Tistory-Blog-000000?style=for-the-badge&logo=tistory&logoColor=white"/></a>
