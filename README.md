# 🧟 D3D11_Biohazard_Re-2

<div align="center">
  <a href="https://www.youtube.com/watch?v=A86mi0EwGC4">
    <img src="https://img.youtube.com/vi/A86mi0EwGC4/0.jpg" alt="프로젝트 영상" width="600">
  </a>
  <br>
  <sub style="color: gray;">▶️ Click!</sub>
</div>

<br>

> **Note**: 본 프로젝트는 2024년(또는 해당 연도)에 개발된 포트폴리오 아카이빙 저장소입니다.

<br>

## 📅 1. 프로젝트 정보
- **개발 기간:** 2024.05.16 ~ 2024.06.26
- **프로젝트 개요:** DirectX 11 API를 활용하여 *Biohazard RE:2*의 핵심 시스템을 모작한 프로젝트입니다. 엔진의 기본 구조부터 조명, 물리 판정, AI 로직 등을 심도 있게 분석하여 3D 게임 엔진의 작동 원리를 파악하는 데 중점을 두었습니다.

<br>

## 🛠 2. 기술 스택
- **Language:** C++, HLSL
- **Graphics API:** DirectX 11
- **Tools:** Visual Studio 2022, FBX SDK

<br>

## 👥 3. 역할 분담

| 이름 | 담당 역할 |
| :--- | :--- |
| **이나영 (ME)** | UI, 미니맵, 퍼즐, UI/Effect Tool |
| **염형준** | 몬스터 애니메이션, 컷신, Monster Tool |
| **이정현** | 프레임워크, 충돌 처리, 이펙트 |
| **조현진** | Shader, 플레이어 |
| **신창균** | UI, 인벤토리 |
| **김예은** | 맵, 퍼즐, 기믹 |

<br>

## 💻 핵심 구현 
> **플레이어 인터렉션 오브젝트와 관련된 UI, 퍼즐 콘텐츠를 전담했으며, 프로젝트 시작 전에는 팀 협업 효율을 위한 UI/Effect Tool을 구현했습니다.** <br>

### 1. 렌더링 최적화 
- **Dynamic Object Culling**: 공간 분할 및 내적(Dot Product)을 활용한 렌더링 선별 (30FPS -> 60FPS)
- **Mesh Instancing**: 동일 객체 다수 렌더링 시 드로우 콜 최적화

### 2. 엔진 아키텍처 
- **Component System**: 상속 구조의 한계를 극복하기 위한 컴포넌트 기반 설계 (Unity 방식 채택)
- **Prototype Pattern**: 객체 생성 비용 절감을 위한 원본 복제(Clone) 시스템 구현

### 3. 자체 제작 툴 
- **ImGui Editor**: 런타임 중 라이팅, UI, Effect 애니메이션 속성을 제어하는 타임라인 에디터 구현
- **UI 구현** : 자체 제작 에디터를 활용해 번거로운 반복 작업 필요 없이 빌드 시간 90% 감축하여 복잡한 미니맵 UI 등을 제작



