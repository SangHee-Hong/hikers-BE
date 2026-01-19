# 🏔️ Hikers (하이커스) - Backend

> **모든 도전과 성장의 발자국이 헛되지 않도록, 등산 올인원 플랫폼 하이커스(상위 8팀 본선 진출🎉)**  
> 2025 서울 열린데이터광장 공공데이터 활용 창업 경진대회 출품작 
<img width="1240" height="696" alt="image" src="https://github.com/user-attachments/assets/9354699c-6a64-45a1-9bbb-717bd35929a0" />

## 📖 프로젝트 소개

 **하이커스(Hikers)** 는 등산 정보 습득부터 커뮤니티 활동, 산행 기록 인증까지 등산의 전 과정을 지원하는 올인원 플랫폼입니다.  분산된 공공데이터(등산로, 날씨 등)를 통합하여 신뢰도 높은 정보를 제공하고, 게이미피케이션(스탬프, 랭킹) 요소를 통해 지속적인 산행을 독려합니다.

본 리포지토리는 하이커스 서비스의 **REST API 서버**를 담당하는 백엔드 프로젝트입니다.

## 🛠 Tech Stack

### Backend
- **Language:** Java 17
- **Framework:** Spring Boot 3.x
- **Database:** MySQL 8.0 (AWS RDS)
- **ORM:** Spring Data JPA
- **Server:** AWS EC2
- **Web Server:** NGINX (Reverse Proxy)
- **Storage:** AWS S3 (Image Storage)
- **Build Tool:** Gradle

### Infrastructure
- **Cloud:** AWS (EC2, RDS, S3, CloudFront, Route53)

### Data & External APIs
- **Korea Forest Service:** 100대 명산 GPX 데이터 (등산로 경로, 고도, 거리)
- **Seoul Open Data Plaza:** 서울시 실시간 도시데이터 API (산지 날씨, 미세먼지)


## 🏛 System Architecture
<img width="1229" height="674" alt="image" src="https://github.com/user-attachments/assets/9ece7109-e9da-4434-9b78-82dfecb257dd" />


## Key Features (Backend)
<img width="1759" height="981" alt="image" src="https://github.com/user-attachments/assets/632f7fc3-0941-4a49-98c8-b8d79ee40a68" />
<img width="1786" height="988" alt="image" src="https://github.com/user-attachments/assets/23ab1df7-7f14-45d4-8822-9ec26567f526" />
<img width="1787" height="1000" alt="image" src="https://github.com/user-attachments/assets/91c4cf40-259c-4649-88ab-7cb589b470df" />
<img width="1781" height="996" alt="image" src="https://github.com/user-attachments/assets/f74577ad-0bb0-4486-a6eb-c0c45644e68b" />
<img width="1787" height="986" alt="image" src="https://github.com/user-attachments/assets/f646b467-204b-4c06-9297-22481e989df8" />
<img width="1796" height="1010" alt="image" src="https://github.com/user-attachments/assets/374d465d-b9ea-48b4-9570-64bd864df2d5" />


## ERD
<img width="2056" height="1141" alt="image" src="https://github.com/user-attachments/assets/1fafd29d-8831-45b7-b203-0fd7ef47d9cb" />

## Getting Started

### Prerequisites
- Java 17+
- MySQL 8.0+

### Installation
1. **Clone the repository**
```bash
git clone https://github.com/your-username/hikers-backend.git
cd hikers-backend
```








