# nltk 설치
1. 아나콘다 프롬프트 관리자권한으로 실행
2. Pip install nltk 로 설치여부 확인
3. 설치 되어있으면 주피터에서 import nltk
4. Nltk.download() import 해서 all 다운

# 한국어 nltk 파일 다운
1. 비주얼스튜디오 빌드 툴 필요(아래 링크로 다운)
    * https://visualstudio.microsoft.com/ko/downloads/
    * 아래 Tools for Visual studio 2019 클릭
    * Visual Studio 2019용 Build Tools 다운로드
    * 설치
2. Visual C++ 빌드도구 선택 및 설치(C드라이브 6GB 필요)
3. cmd 관리자권한으로 실행
    * `pip install --upgrade pip`
    * 에러가 나면 다시 실행
4. 환경변수 설정
    * 설정된 JAVA_HOME을 `C:\Program Files\Java\jre1.8.0_271\bin\server`로 변경
    * 차후 다시 되돌릴 예정
    * path에도 JAVA_HOME 내용 삭제
5. jpype 설치
    * `conda install -c conda-forge jpype1`
6. konlpy 설치
    * `pip install konlpy`
---
## 파이썬과 jpype버전이 맞지 않는 경우
- 다시 삭제
`conda remove jpype1`
- 다운
url : https://www.lfd.uci.edu/~gohlke/pythonlibs/#jpype
JPype1-1.2.0-cp38-cp38-win_amd64.whl 선택해서 다운
- 설치
`C:\Windows\system32>cd C:\Users\204\Downloads`
`C:\Users\204\Downloads>pip install JPype1-1.2.0-cp38-cp38-win_amd64.whl`

# 문서군집 샘플
- 실습데이터 : OpinosisDataset1.0
	- https://cafe.naver.com/ctraining/2943

# cx_oracle 설치 법
- anaconda prompt 관리자 모드 실행
- `pip install cx_oracle` 실행
- data.csv 옮기기(data_analysis)
