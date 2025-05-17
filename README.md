# 🫧 XREAL 학회 과제 

**XREAL 학회**에서 진행한 **전반기(Unity AR)** 및 **후반기(VR)** 과제를 정리한 공간입니다.  
기술 학습을 목적으로 Unity 기반으로 제작된 두 가지 과제를 담고 있습니다.

---

## 🎄 Magic Santa (전반기 미니게임 과제)

**Magic Santa**는 Unity와 C#을 활용해 제작한 **3D 미니게임**입니다.  
플레이어는 산타를 조작해 적을 공격하고 생존하며, 다양한 Unity 기능을 직접 구현했습니다.

### 🎮 주요 기능
- 🎯 **오브젝트 풀링**: 성능 최적화를 위한 총알/이펙트 관리
- ✨ **파티클 이펙트**: 산타 공격 시 마법 효과 출력
- ❤️ **HP 및 데미지 시스템**: 산타와 적 모두 체력 관리 및 공격 처리
- ♻️ **싱글톤 패턴**: 게임 매니저 및 UI 관리 최적화
- 🔁 **FSM (Finite State Machine)**: 적의 상태 제어
- ⚔️ **스킬 시스템**
  - **E 키**: 기본 스킬 (광역 마법 공격, 짧은 쿨타임 적용)
  - **F 키**: 궁극기 스킬 (강력한 전체 공격, 긴 쿨타임 적용)

### 🎞 게임 화면 (GIF)
<p align="center">
  <img src="images/magicSanta.gif" width="600"/>
</p>

---

## 🧱 VR Jenga (후반기 MetaXR 기반 VR 과제)

**VR Jenga**는 Meta Quest3 디바이스와 MetaXR SDK를 활용하여 제작한 **VR 물리 퍼즐 게임**입니다.  
플레이어는 실제 공간 위의 책상에서 VR 젠가 블록을 잡고, 무너지지 않도록 조심스럽게 조작합니다.

### 🕹 주요 기능
- 📦 **Jenga 블록 상호작용**: 손으로 블록을 잡는 직접적 물리 상호작용
- 🧠 **게임 룰**: 블록이 바닥으로 떨어지면 게임 종료
- 🖲 **Rebuild 버튼**: 책상 중앙의 버튼을 누르면 무너진 젠가가 초기 상태로 복구됨

### 🎞 게임 화면 (GIF)
<p align="center">
  <img src="images/vrjenga.gif" width="600"/>
</p>

---

## 🛠 사용 기술

| 과제       | 사용 기술 |
|------------|-----------|
| Magic Santa | Unity, C#, Animator, FSM, 오브젝트 풀링, 싱글톤, 파티클, 스킬 쿨타임 |
| VR Jenga    | Unity, MetaXR SDK, VR Interaction Toolkit, Rigidbody Physics |

---

## 📚 학습 목적

본 과제들은 각각 **게임 개발 기초와 AR/VR 인터랙션 설계**를 중심으로 구성되었습니다.

- **전반기(Unity 3D 게임)**: Unity의 기본 구조 이해, C# 기반 로직, 상태 패턴, 최적화 기법 학습
- **후반기(VR 프로젝트)**: MetaXR 환경에서의 손 인터랙션, 현실 기반 오브젝트 배치, VR UX 고려

---

## 🧑‍💻 개발자

- **나우진 (Woojin Na)**  
- 📧 [uujin314@icloud.com](mailto:uujin314@icloud.com)

---
