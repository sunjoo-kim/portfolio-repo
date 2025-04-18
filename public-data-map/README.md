# 🗺️ 공공데이터 기반 지역 특성 시각화 프로젝트

## 🔹 프로젝트 개요
- 지역별 교통/문화/편의시설 데이터를 가공하여 지도 위에 시각화
- 공공데이터를 활용한 데이터 수집 및 가공
- Spring Boot 기반 API + Terraform을 활용한 AWS 인프라 배포

## 🔹 구조
- `backend/`: Spring Boot API 서버
- `data-processing/`: Python 기반 데이터 정제 및 MySQL 적재
- `infra/`: Terraform을 활용한 인프라 구성 (EC2, RDS, S3)

## 🔹 사용 기술
- Spring Boot, MySQL, Python (pandas)
- AWS (EC2, RDS, S3), Terraform

## 🔹 주요 기능
- 법정동 기준 데이터 요청 API
- 평가 항목별 필터링 기능
- 지도에 표출할 수 있도록 JSON 포맷 제공
