# git-test


## 용어

### git
컴퓨터 파일의 변경사항을 추적하고 여러 명의 사용자들 간에 해당 파일들의 작업을 조율하기 위한 분산 버전 관리 시스템

### local
- 사용자 컴퓨터에 존재하는 모든 것
- 실제로 내가 작업하는 공간(컴퓨터)

### remote
- github 상에 존재하는 모든 것
- 원격 저장소

### origin
- remote에 존재하는 repository

### upstream
- upstream과 downstream은 상대적인 개념으로 두 repository의 상하 관계에 따라서 정의
- upstream은 근원이 되는 repository를 의미
- 다른 repository에서 fork해서 내 repository로 가져옴
  - upstream = fork한 repository
  - downstream = origin(내 repository)
- 내 repository에서 local로 pull을 해옴
  - upstream = origin(내 repository)
  - downstream = local
