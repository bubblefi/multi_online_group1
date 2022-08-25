# multi_online_group1

# 최예은
- 브랜치 생성

# 안녕하세요
- online group1 원지유입니다.
- 팀 미션 진행 중입니다.

# 윤선호

- 늦었습니다.죄송합니다


# 오전 미션
1. 팀 깃허브
2. readme.md 를 각자의 브랜치로 생성 (자기 이름으로 된 브렌치 만듬)
3. readme.md 파일 각자 작성 후
4. main 브랜치에 모두 병합

# ~12시까지 수업
 - reset
 - 브랜치 백업
 - revert (되돌리기)

------------------




##오후 팀별 미션
1. main 브랜치 생성
2. 자신의 브랜치에 준비한 자료들을 업로드(이미지, 폰트, 다양한 자료들)
3. main 브랜치에 병합
4. 폴도 구조 등은 개발자들끼리 협의
5. 리소스 폴더를 구성하고 
6. Readme.md 파일에 매뉴얼을 작성
merge, rebase 상관 없음
7. 1회 이상 revert 사용 후 커밋하기
8. Readme.md 파일에 팀원들 수고하셨습니다. 인사들 각자 남기기
9. 최종적으로 만든 main 깃허브 감상

# 메뉴얼
- 메뉴얼을 작성해주세요

<<<<<<< HEAD
Git 기초 명령어
 - git clone [원격저장소] [로컬저장소] : 원격 저장소를 복사
- git add : 스테이지에 올리는 작업 (stage)
- git commit : 스테이지 영역에 있는 작업을 커밋으로 만듬 (커밋이라 함은....일종의 작업 단위)
- git push : 원격 저장소에 커밋을 올린다

코드 뭉치 버리기
- commit 활동을 하기 이전에 그냥 작성했던거 버림

브랜치 생성 및 변경
- git branch : 기존 내용을 유지하고 새로운 기능이나 내용 추가 하고 싶을 때마다 브랜치 생성
- git checkout :  특정 브랜치에서 작업을 하고 싶을 때 체크아웃을 해야함
- 소스트리에서 체크아웃은 브랜치 이름을 더블클릭하기만 해도 변경되므로 편리

병합
- git merge 
: 서로 작업한 부분이 겹치지 않는 경우 그냥 병합이 일어남 (fast-forward)
: 서로 작업한 부분이 겹치는 경우에는 진짜 병합을 해야함 -> 충돌 발생 -> 충돌 해결

충돌해결
- 에디터에서 직접 코드 작성했던 담당자들이 모여서 최종 코드를 함께 완성(co-programing)
- 근데 확인해보니 둘중 한쪽 코드는 버려도 될 경우에는 저장소것 사용 또는 내것 사용 등을 선택해서 적용

stash
- 체크아웃전, 커밋하려던 내용을 임시로 보관
- 유용하다

rebase
- 사실상 merge인데 현재 브랜치가 대상 브랜치보다 더 상위로 바꿀 때
- 위험하니 조심스럽게 사용할 것
(강사님이 올려주신거 그대로 기입함)

(되돌리기 3가지 방법)
--
되돌리기
reset
 - 아예 커밋 자체를 다 되돌려 놓음
 - 사용이 간단
 - 작업들 다 날라갈 수 있음
------
브랜치
 - 브랜치를 백업으로 이용하는 방법
(되돌리기(reset) 방식이 더 편할 수 있음. 실제로 그시점이 되어봐야지 암)
(update-branch를 따로 만들어서 백업으로 활용)

 장단점
 - 백업을 브랜치로 남겨두었으므로 충돌은 많진 않다.
 - 브랜치 점점 복잡해짐

------
revert
(직관적)
 - 되돌리기를 커밋으로 남기는 방법!!
 되돌리기는 빨리할수록 다른 사람과의 혼동이 안생김

- 되돌리기에 대한 기록이 남김
- 되돌리기를 되돌리기를 할 수 있음.
다만, 커밋목록이 남음

2번 이상 반복시에, reset(초기화)를 진행

 장단점
 - 충돌 해결 이슈

*******
다른 팀원과 소통이 안된 상태에서
reset, branch, revert 진행할 경우 큰일남!!

<<<<<<< HEAD


# 인사
- 팀원분들 수고하셨습니다! 도움 주셔서 감사합니다. Online 1 group_원지유
=======
# 최예은
- 다들 수고하셨습니다. 너무 어렵네요 다들 화이팅!
>>>>>>> d97d886739de15909062d5a43fdf7f74dce56bec
