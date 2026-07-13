# 자동매매

AI 모델 기반 주식 자동매매 프로그램을 만들기 위한 실험 프로젝트입니다.

## 현재 단계

- KOSPI 시가총액 상위 30개 종목 수집
- KOSDAQ 시가총액 상위 30개 종목 수집
- 상위 60개 종목의 일봉 OHLCV 데이터 수집

## 주요 파일

- `자동매매작업1.ipynb`: 데이터 수집 노트북
- `작업프로세스.txt`: 작업 메모

## 환경 준비

```bash
pip install pandas numpy matplotlib seaborn scikit-learn finance-datareader tqdm
```

## 데이터

수집 데이터는 `data/` 폴더에 저장됩니다. 현재 `.gitignore`에서 제외되어 있어 GitHub에는 올라가지 않습니다.
