# 프로젝트 이름 :   
### ClimateMarketForecast    
<br>
  
# 프로젝트 주제 :   
기후 변화와 도매시장 데이터를 기반으로 한 시계열 예측 모델링. 기후 데이터와 도매시장의 품목별 거래 현황을 분석하여 미래의 거래 흐름을 예측하는 모델을 개발.  
<br>
  
# 프로젝트 목표 :   
농산물 품목별 도매시장 경매 평균단가 예측
<br>

## 폴더구조
```plaintext
📁 FESTIVAL
├── 📁 analysis       --- 데이터 분석 및 시각화
├── 📁 crawlings      --- 데이터 수집 코드
├── 📁 data           --- 실제 분석/모델에 사용된 데이터
│   └── 📁 processed  --- 전처리된 데이터 
│   └── 📁 raw        --- 원본 데이터 
├── 📁 db             --- db 관련 코드
├── 📁 models         --- 모델 관련 코드
├── 📁 preprocessing  --- 전처리 코드 
├── 📁 saved_models   --- 학습된 모델 저장
├── 📁 web            --- Django 프로젝트 폴더
│   └── 📁 routes     
│   └── 📁 services   
│   └── 📁 static     
│   └── 📁 templates  
│   └── 📄 app.py     --- web 실행 파일
│   └── 📄 config.py  --- web 설정 파일
├── 📄 .gitignore     --- Git 무시 파일 설정
├── 📄 README.md      
└── 📄 requirements.txt --- 설치 파일 
```
<br>

## 설치 방법
```bash
pip install -r requirements.txt
```