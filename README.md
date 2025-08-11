# ProjectTTW

**내용 정리 중**

Content폴더는 용량이 큰 파일이 있어 Release에서 다운받아 주세요.

- 핵 앤 슬래쉬, 전략 전술 장르 모작 프로젝트

- 프로젝트 기간 : 2025년 5월 14일 ~ 2025년 6월 10일

- 개발 엔진 : UnrealEngine 5.5

- 게임 플레이 영상

- 형상 관리 : TortoiseSVN

  [![Prorect TTW 시연영상](http://img.youtube.com/vi/_vSz0Fo4x4Q/0.jpg)](https://youtu.be/_vSz0Fo4x4Q)

### 담당한 작업
- [9dyy](https://github.com/9dyy)
  - 팀장으로서 전체적인 프로젝트의 기획 및 일정 관리
  - Formation(진형 갖추기) 기능 구현
    - 그림을 그려서 아군 AI를 배치(진형 갖추기)하는 기능 구현
    - 진형 저장 시스템 구현
  - 적 및 아군 AI 구현
- [wonsub](https://github.com/wonsub) - 메인 캐릭터 담당
  - 전투 시스템 개발
      - 상태 머신을 기반으로 공격 애니메이션
      - 콤보 입력 처리
      - 히트 판정 및 피격 반응 시스템 구현
  - 회피 시스템 구현
     - 입력 방향 기반 회피 동작(스텝→구르기)
  - 패링(Parry) 시스템
     - 타이밍 기반 반응 처리
     - 적의 공격을 무효화 및 넉백
  - 타겟 락온 시스템
     - 근처 적 탐색 및 전환 기능 구현
     - 카메라와 이동 방향 연동 처리
  
- [kwon-h-chan](https://github.com/kwon-h-chan)
  - 스테이지 내 미니맵 구현
  - 스테이지 에셋 적용

### 사용한 에셋
- NPC 최적화 플러그인 - [NPC Optimizator - automatic optimize NPC for you game](https://www.fab.com/ko/listings/8ecf84fa-0b4e-4e00-a696-638e1ee7b6ec)
- 배경 - [Landscapes Pack](https://www.fab.com/ko/listings/c6a8fa58-84f1-4bb8-935d-a3467e9fe58d)
- 주인공 캐릭터 - [Paragon: Kwang](https://www.fab.com/ko/listings/f4c67e92-b976-4b5b-ab9f-4c25b010f6f3)
- 적 AI
  - 스켈레탈 메시 - [Skeleton Guard (Modular)](https://www.fab.com/ko/listings/e6d40511-9e66-4fd9-be1c-7032099c0d75)
  - 창 공격 애니메이션 - [Mega Spear Animation Pack](https://www.fab.com/ko/listings/a6f8de4a-b0a3-4b9b-8afc-bd6f1bf20bfa)
    

