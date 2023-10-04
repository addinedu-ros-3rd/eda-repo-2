# EDA 프로젝트 2조 
서울시 맛집 데이터 분석 & 맛집 추천 및 시각화 프로그램 개발

## 주요 라이브러리
* 언어: Python
* 크롤링: Selenium, Beutifulsoup
* 데이터 분석: matplotlib, seaborn, pandas, scipy
* GUI 시각화: 
```
PyQt5==5.15.6
pyinstaller==5.13.2
tk==0.1.0
tkinterhtml==0.7
wordcloud==1.9.2
selenium==4.11.2
googlemaps==4.10.0
```
## 실행 방법
### 데이터 크롤링
Crawling & analysis 폴더로 이동
1. [Final_with_detail] project.ipynb 파일을 실행하여 서울시 주요 역에 대한 맛집 데이터 크롤링(상세 리뷰 포함)
   * 크롤링 결과를 '../data/1기본_OO역.csv'로 저장
3. [Final_without_detail] project.ipynb 파일을 실행하여 서울시 주요 역에 대한 맛집 데이터 크롤링(상세 리뷰 미포함)
   * 크롤링 결과를 각각 '../data/2상세_OO역.csv'로 저장
![project](https://github.com/addinedu-amr-4th/eda-repo-2/assets/87626122/8816bef4-95f6-4551-8c4d-f2bb39f04193)

### 데이터 분석
Crawling & analysis 폴더에서 retaurant_analysis.ipynb 파일을 실행하여 분석 및 시각화 결과 확인


![grpah1](https://github.com/addinedu-amr-4th/eda-repo-2/assets/87626122/67e8fed6-c27a-4168-ae59-c3ea3a5a1c50)


![word_cloud](https://github.com/addinedu-amr-4th/eda-repo-2/assets/87626122/db99c56f-61d7-4df8-8f4a-cff96147a0c4)


![gasan](https://github.com/addinedu-amr-4th/eda-repo-2/assets/87626122/faa2bd83-654c-4bb8-a72a-bf43c50e2a99)

![gangnam3040](https://github.com/addinedu-amr-4th/eda-repo-2/assets/87626122/6b4e5e0b-204a-46fb-bb4d-7f0cff92bbd3)




## 서울시 지역별 맛집 점수화 및 DataFrame 생성

![image](https://github.com/addinedu-amr-4th/eda-repo-2/assets/97663670/cec0454b-2a65-4e6d-8b83-3acca1486f22)

```
️❓ ** 역 별 맛집은 알겠는데.. 가시성을 개선하고 싶다. **
💡 ** 시각화 및 GUI화 !! **
```
1. Folium, 맛집 정보 시각화

2. Tkinter, 맛집 정보 GUI화

3. Pyinstaller, 코드 배포를 위한 프로그램화

## 서울시 지역별 맛집 추천 프로그램 : 쩝쩝박사.exe

> Tkinter를 사용해 맛집 추천 GUI 창 생성
/
> Pyinstaller를 사용해 파이썬 코드의 실행 프로그램화 
![image](https://github.com/addinedu-amr-4th/eda-repo-2/assets/97663670/b1d2f0ce-9f12-4f6f-a23e-24fea6040ba6)

### 프로그램 개요도
![image](https://github.com/addinedu-amr-4th/eda-repo-2/assets/97663670/978425d6-ba60-4517-9434-df9a8e56b32a)

