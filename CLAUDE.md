# Data Analyst Portfolio — Claude 컨텍스트

## 프로젝트 개요
- **목적**: 데이터 분석가 취업용 GitHub 포트폴리오
- **GitHub**: https://github.com/imyourcatfood/Data-Analyst-Portfolio
- **소유자**: 최서원 — 수학교육과 졸업, 에듀테크 PM 3년8개월, 데이터 분석가 부트캠프 수료 (2026.03)
- **기술 스택**: Python, SQL, Tableau, Excel/Google Sheets, Pandas, Plotly, Selenium

## 워크플로우 규칙 (필수)
- **모든 변경은 사용자 승인 후 진행** — 파일 생성·수정, 커밋, PR 등 어떤 작업이든 먼저 보여주고 승인받을 것
- 작업 브랜치: `codex/<task-name>` 패턴 (예: `codex/add-ccommerce-notebook`)
- `main` 직접 커밋 금지 → 항상 feature branch → PR 경유
- 내부 메모·초안은 `.codex/` 폴더에만 저장 (.gitignore 처리됨)

## 프로젝트 구조

| 폴더 | 프로젝트 | 상태 |
|------|---------|------|
| `instacart-analysis/` | Instacart 고객 리텐션 분석 (SQL + Python) | ✅ 완료 |
| `china-ecommerce-analysis/` | 중국 C-commerce 패션 카테고리 성장 분석 | 🔄 노트북 업로드 필요 |
| `seoul-apartment-analysis/` | 서울 아파트 가격 회복 Tableau 대시보드 | ✅ 완료 |
| `meta-ads-analysis/` | 주얼리 이커머스 메타 광고비 절감 분석 | ⏳ 미착수 |

## 로컬 데이터 파일 위치

### C-commerce 프로젝트
- **작업 디렉토리**: `/Users/seowon/China-ecommerce/`
  - `ccommerce_analysis_clean.ipynb` — 정제 노트북 (미완성, 업로드 전)
  - `Youtube_title.ipynb` — 유튜브 스크래핑 분석 원본
  - `youtube_data.csv`, `youtube_titles.csv` — 유튜브 제목 데이터
  - `패션의류_수출입실적.xlsx` — 한국 의류 수출입 단가 데이터
  - `ali_temu_survey_reconstructed_410_v2.xlsx` — 소비자 설문 (410명)
  - `china_data.csv` — 관세청 해외직구 통계
  - `korea_data.csv` — KOSIS 국내 온라인쇼핑 거래액
  - `Total Analysis_final.ipynb` — 팀 원본 분석 노트북

### 발표자료 / 포트폴리오
- **PPT**: `/Users/seowon/Downloads/포트폴리오/` (C-commerce_ppt.pdf 등)
- **포트폴리오 PDF**: `/Users/seowon/Desktop/개인 서류/DA_이력서/포트폴리오_최서원.pdf`

## 현재 미완성 작업
`ccommerce_analysis_clean.ipynb`에 추가 필요한 섹션:
1. **유튜브 카테고리별 카운트 그래프** — `youtube_data.csv` 기반, 테무/알리 관련 영상 카테고리 분포
2. **국내 백화점 vs 중국 직구 비교** — 백화점 패션 매출 감소 시점과 C-commerce 성장 시점 연관
3. **수출입 의류단가 비교** — `패션의류_수출입실적.xlsx` 기반, 한국 수출단가 vs 중국 수입단가

완성 후 `china-ecommerce-analysis/` 폴더에 업로드하고 PR 머지 필요.
