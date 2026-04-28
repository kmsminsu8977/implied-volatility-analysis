# 발표 초안

## 1. 문제 정의

같은 만기에서 행사가별 시장가격은 어떤 변동성 구조를 암시하는가?

## 2. 데이터와 가정

- 합성 샘플 데이터: `data/sample/market_option_quotes.csv`
- 재현 가능한 baseline 실행을 우선 구성

## 3. 방법

시장 옵션가격에서 Black-Scholes 내재변동성을 역산하고 smile 구조를 해석한다.

## 4. 현재 산출물

- 실행 스크립트: `python -m src.run_baseline`
- 결과 표: `outputs/tables/baseline_results.csv`

## 5. 후속 작업

- 실제 데이터 연결
- 민감도 분석
- 차트/보고서 산출
- 프로젝트별 상세 검증
