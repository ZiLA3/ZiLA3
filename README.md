## 출시작

### [Luminous Witch](https://github.com/ZiLA3/Witch) — 로그라이크

`Unity 6` `C#` `Git`

**2025.07 ~ 2025.12 (6개월)** · 4인 팀 (아트/UI 2, 기획 1, 프로그래밍 1)
**팀장 · 클라이언트 개발 전담 · 빌드/배포 전 과정**

> 스토브 인디 데모 정식 출시 · 비버락스 2025 출품

- **스킬 시스템** — 쿨타임·코스트 같은 공통 수치는 `ScriptableObject`로, 코드로만 표현되는 동작은 `Behavior` 클래스로 분리. 기획자가 인스펙터에서 직접 밸런싱할 수 있게 설계했고 이 구조로 스킬 20종을 구현했습니다.
- **로그라이크 시스템** — 랜덤 시드 맵/보상, 스킬 재조합, 상점 구현
- **VFX · 셰이더** — 담당 인원이 없어 필요한 최소한을 직접 학습 후 구현
- **빌드 · 배포** — 스토브 인디 심의부터 스토어 페이지까지 담당

🎮 [스토브 인디](https://store.onstove.com/ko/games/103045)

<img width="960" height="540" alt="LuminousWitch1" src="https://github.com/user-attachments/assets/751709e8-ece4-4067-88e8-90e6bf7ba0f0" />

<details>
<summary>스크린샷 더보기</summary>
<img width="960" height="540" alt="LuminousWitch2" src="https://github.com/user-attachments/assets/3c2e84e7-bf3c-4b41-a7a2-d454519c8960" />
<img width="960" height="540" alt="LuminousWitch4" src="https://github.com/user-attachments/assets/10f3040f-c778-4884-9454-c5e6e0f143c1" />
<img width="960" height="540" alt="LuminousWitch3" src="https://github.com/user-attachments/assets/0c4366fc-8a78-43cf-9fd8-5a9f7804a09a" />
</details>

---

## 개발 중

### 미니미즈 (Minimis) — 개척 시뮬레이션

`Unity` `C#` `Git`

**2026.01 ~ 진행 중** · 4인 팀 · 팀장 · 클라이언트 개발 전담

미니미들이 작은 SF 자판기에서 살아남아 탈출하는 게임입니다.

- **코어와 UI 분리** — `MonoBehaviour`에 붙어 있던 게임 로직을 `UnityEngine` 참조가 없는 순수 C#으로 분리. 플레이 모드 없이 테스트를 돌릴 수 있게 되었고, 정적 변수 초기화 순서 버그처럼 플레이로는 재현이 어려운 문제를 잡았습니다. (2개월 소요)
- **행동 최소 단위 분해** — 이동·대기·실행·조건 판정을 `Step`으로 쪼개고 실패 조건을 각 Step에 붙여, 새 작업 대부분을 기존 Step 조합만으로 구성
- **레이어 규칙 문서화** — 계층 간 읽기/쓰기 방향을 네 줄 판정표로 고정하고, AI가 분류·커밋한 변경분을 판정표로 검증

🎮 [웹 빌드](https://zila3.itch.io/minimis) · ▶️ [플레이 영상](https://youtu.be/gzA-F5sM7vA)

### 불새 — 스토리 퍼즐

`Godot 4` `GDScript`

**2026.05 ~ 진행 중** · 4인 팀 · 팀장 · 클라이언트 개발 전담

불새를 피해 도망가는 스토리 진행 중심의 2D 퍼즐입니다.

- **C# → GDScript 전환** — Godot 4가 C# 웹 내보내기를 지원하지 않아, 언어 숙련도보다 이터레이션 속도를 우선해 한 달에 걸쳐 전환. 팀 전원이 설치 없이 링크만으로 최신 빌드를 플레이할 수 있게 되었고, 배경 색감·환경 배치·퍼즐 난이도가 이 피드백 루프에서 정리됐습니다.

🎮 [웹 빌드](https://zila3.itch.io/firebird) · ▶️ [플레이 영상](https://youtu.be/tANDuvlaXXk)

---

## Sub Projects

| 프로젝트 | 설명 |
| --- | --- |
| I-Tracker | MediaPipe 기반 아이트래킹 공포 게임 |
| [F1-QualifyingScore](https://github.com/ZiLA3/F1QualifyingDriverScore) | F1 데이터 상관관계 분석 |

---

## Contact

📄 포트폴리오 · ✉️ kms-0509@naver.com
