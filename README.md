# 2025 삼성전자판매 VOC 분석 대시보드

2025년 1~6월 사내 VOC 788건과 외부 KCSI·재무 데이터를 통합 분석한 단일 HTML 대시보드.

## 🔗 라이브 URL

👉 **<https://samsungsales445.github.io/voc-dashboard/>**

## 📊 주요 기능

- **Summary** — 전체 VOC 한눈에 톺아보기 (Leaflet 지도, 분류 v2 6개 카테고리)
- **Analysis** — by Sales / by Age / by Type 다층 분석
- **VOC List** — 788건 전체 리스트 검색
- **Comparison** — KCSI 가전유통 4사 4개년 추세, LG 모바일 사업 종료 효과 분석
- **Report** — 4섹션 화면 보고서 + 14페이지 정식 PDF 보고서 생성

## 🛠 사용 기술

- 단일 HTML (외부 의존성: Leaflet, Chart.js, html2pdf.js, Noto Serif KR)
- 빈티지 잡지 톤 디자인 (크림 베이지 #F4E4C1 + 와인 #4A0E2A + 오렌지 #FB7140)

## 📚 데이터 출처

- 사내 VOC 788건 (12차 화이트리스트 노이즈 필터로 정제)
- 한국능률협회컨설팅 KCSI 가전유통 부문 2022~2025
- DART 감사보고서 (삼성전자판매·하이프라자·롯데하이마트·전자랜드)
- CRETOP 기업정보
- 롯데하이마트 ESG 보고서 5개년 (2020~2024)
- 행안부 인구 통계 + KOSIS 1인당 개인소득

## 📁 구조

```
.
├── index.html          # 메인 대시보드 (= dashboard.html)
├── dashboard.html      # 동일 파일 (호환용)
└── assets/             # KCSI·ESG 원본 PDF + 인트로 이미지
```
