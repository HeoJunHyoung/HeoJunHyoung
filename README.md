<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:8E2DE2,100:4A00E0&height=220&section=header&text=Crafting%20Reliable%20Backend%20Systems&fontSize=32&fontColor=FFFFFF&desc=MSA%20%7C%20Cloud%20%7C%20DevOps&descSize=18&fontAlignY=35" />
</div>

## 🧑‍💻 About Me

> **"확장 가능한 아키텍처와 대용량 트래픽 처리에 집중하는 백엔드 개발자입니다."**

안정적인 서비스 운영을 위한 **MSA(Microservices Architecture)** 설계와 **시스템 성능 최적화**에 깊은 관심을 가지고 있습니다.  
비즈니스 요구사항을 기술적으로 해결하는 과정에서 발생하는 트레이드오프를 분석하고, 데이터 기반의 의사결정을 지향합니다.


```java
public class HeoJunHyoung {
    private final String email = "gjwnsgud4016@gmail.com";
    private final String blog = "https://receiver40.tistory.com";
    
    public void contact() {
        System.out.println("Ready to build scalable architecture.");
    }
}
```

---





## 🛠️ Tech Stack

### **Backend**
![Java](https://img.shields.io/badge/Java-17-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.5.x-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Cloud](https://img.shields.io/badge/Spring%20Cloud-2025.0.0-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![QueryDSL](https://img.shields.io/badge/QueryDSL-5.1.0-007396?style=for-the-badge)

### **Infrastructure & DevOps**
![Kubernetes](https://img.shields.io/badge/Kubernetes-On--Premise-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-GitOps-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-CI%2FCD-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-22.04%20LTS-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-IaC-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)

### **Data & Messaging**
![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-pgvector-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-6.0+-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-Caching-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-EDA-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)

### **Testing & Monitoring**
![k6](https://img.shields.io/badge/k6-Load%20Testing-7D64FF?style=for-the-badge&logo=k6&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

<br/>

---

## 🚀 Featured Projects

### [🔗 GotEEgo: 사용자 성향 맞춤 여행 메이트 추천 플랫폼](https://github.com/heojunhyoung/goteego-backend/tree/dev)
> **AWS EKS 기반 클라우드 네이티브 아키텍처와 벡터 검색을 활용한 개인화 추천 서비스**

| 주요 기능 | 기술적 특징 및 해결 과제 |
| :--- | :--- |
| **Vector Search 추천** | • **PostgreSQL pgvector** 확장을 도입하여 사용자 성향(User Embedding)과 여행지 간 **Cosine Similarity** 연산 구현<br>• 단순 필터링을 넘어선 정교한 취향 기반 매칭 알고리즘 설계 |
| **Cloud Native Infra** | • **AWS EKS** 환경에서 Terraform(IaC)을 활용한 인프라 프로비저닝 및 관리<br>• **ArgoCD** 기반 GitOps 파이프라인 구축으로 매니페스트 변경 사항 자동 동기화 |
| **확장성 있는 채팅** | • **Redis Pub/Sub** 아키텍처를 적용하여 다중 서버 환경에서 WebSocket 메시지 동기화 문제 해결<br>• **MongoDB**를 도입하여 대용량 채팅 로그 쓰기 성능 확보 및 조회 최적화 (Polyglot Persistence) |
| **성능 최적화** | • **Redis Write-Back 전략**: 게시글 조회수 등 빈번한 쓰기 연산을 메모리에서 처리 후 DB 일괄 반영<br>• **HttpOnly Cookie 핸들링**: 보안을 위한 쿠키 기반 JWT 인증과 WebSocket 핸드셰이크 간 연동 문제 해결 |

### [🔗 LinkFolio: 개발자 포트폴리오 공유 및 채용 플랫폼](https://github.com/HeoJunHyoung/Linkfolio-backend/tree/dev)
> **MSA 기반 대용량 트래픽 처리 시스템**

| 주요 기능 | 기술적 특징 및 해결 과제 |
| :--- | :--- |
| **하이브리드 인프라** | • VirtualBox VM 기반 **On-Premise Kubernetes 3-Node 클러스터** 직접 구축<br>• 외부 메시징 인프라(Kafka VM)와 K8s 클러스터를 분리한 **Hybrid Cloud Topology** 설계 |
| **데이터 동기화** | • **Kafka & Debezium(CDC)** 을 활용한 서비스 간 데이터 실시간 동기화<br>• **Transactional Outbox Pattern**을 적용하여 분산 환경에서 데이터 정합성 보장 (SAGA Pattern) |
| **고성능 검색/조회** | • **Split Caching Strategy**: 정적 데이터(본문)와 동적 데이터(조회수)의 캐싱 라이프사이클 분리<br>• **Redis Write-Back**: 조회수 등 빈번한 업데이트를 메모리에서 처리 후 배치 동기화 (DB Lock 해소) |
| **성능 최적화** | • **k6 부하 테스트**를 통한 병목 구간 식별 및 튜닝 (조회 성능 73% 개선)<br>• 쿼리 실행 계획 분석을 통한 **복합 인덱스(Composite Index)** 적용 및 Full Table Scan 제거 |

<br/>

---

## 📊 GitHub Stats

<p align="center">
  <img height="180em" 
       src="https://github-readme-stats-psi-three-58.vercel.app/api?username=heojunhyoung&show_icons=true&theme=dark" />
  <img height="180em" 
       src="https://github-readme-stats-psi-three-58.vercel.app/api/top-langs/?username=heojunhyoung&layout=compact&hide=jupyter%20notebook,python&theme=dark" />
</p>

