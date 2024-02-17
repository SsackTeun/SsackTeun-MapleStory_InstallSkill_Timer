### 업데이트
---
v1.1
* 기능추가 : 솔 야누스 20초 때 감지 추가
* 문구수정 : 신뢰도 -> 유사도
* 유사도 기본값 수정 : 0.92 -> 0.96
* 유사도 조절 범위 수정 : 0.92 이하는 의미 없는 값으로 보고, 0.92 ~ 1.0 사이로 조절범위 변경
* 문구수정 : 딜레이 -> 감지 후 소리 지연 딜레이 (초) 로 변경

* 라디오 버튼이 더 늘어날 경우, 스킬 + 레벨 구간 + 감지 시점 (10초단위) 이렇게 변경할 예정
* 현재 정상작동하는 해상도는
* 1920x1200, 1920x1080, 1366x768, 1280x720, 1024x768

### 구동화면
---
![image](https://github.com/SsackTeun/MapleStory_InstallSkill_Timer/assets/24308378/7e29a5ae-d48d-4142-ac0a-d2f77f228bd3)


### 사용법 
---
* 기본 값으로 두신 다음 실행버튼을 누르고, 사용하시면 됩니다.
* 솔 야누스는 레벨별로 쿨타임이 다르다고 하여, 오작동이 있다고 하여 나누어서 만들었습니다.

#### [주의] 아래 내용 변경시 중지 버튼을 누르고 수행하여야 반영됩니다.
* 사운드 파일 변경(.wav 확장자)
* 신뢰도 변경
* 딜레이 변경

* 제가 야누스 8레벨 밖에 안되고, 친구는 30레벨이라 20레벨 표본이 없어 테스트는 아직 못해본 상태입니다.
  
### UI 설명

* 신뢰도 : 0.92 = 92% 유사도를 만족하는 스킬을 찾습니다.

* 딜레이 : 찾는 이미지가 "10초" 라는 숫자를 포함합니다. 최소한 9초쯤에는 소리가나야하나, 사운드파일이 2초중 1초가 앞에 비어있습니다.

* ex) 딜레이값을 0 -> 8초 로 향할 수록 "늦게 알림"을 의미합니다. 사냥 스타일에 따라 편하게 조절하시면 됩니다.


### [NOTICE] Exe build
---
* EXE 파일 생성에 사용된 모듈은 "pyinstaller" 입니다

### [NOTICE] dependency
---
* requirements.txt
### 다운로드 1.1v : https://drive.google.com/file/d/1dWrQlEmBLspYscLMpQJlCahwtf2AMfW3/view?usp=sharing  
### 다운로드 0.9v : [https://drive.google.com/file/d/1wJ_2QsbkMd5cVQDfsk2fBreoUUskActv/view?usp=sharing](https://drive.google.com/file/d/1E4nZEGQr6275bq6HIhnyrj41r9zjMQds/view?usp=sharing)






