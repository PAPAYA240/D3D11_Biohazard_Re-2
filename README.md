# 🧟 D3D11_Biohazard_Re-2

<div align="center">
  <a href="https://www.youtube.com/watch?v=A86mi0EwGC4">
    <img src="https://img.youtube.com/vi/A86mi0EwGC4/0.jpg" alt="프로젝트 영상" width="600">
  </a>
  <br>
  <sub style="color: gray;">▶️ Click!</sub>
</div>

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

## 🚀 4. 주요 구현 내용
<br>
- 플레이어 인터렉션 오브젝트와 관련된 UI, 퍼즐 콘텐츠를 전담했으며, 프로젝트 시작 전에는 팀 협업 효율을 위한 UI/Effect Tool을 구현했습니다.
| 📊 **UI (User Interface)** | 🧩 **퍼즐** | 🧩 **최적화** |
| :--- | :--- | :--- |
| **UI 프레임워크** <br> [코드 보러가기](주소) | **퍼즐 프레임워크** <br> [코드 보러가기](주소) | **구역 기반 Culling** <br> [코드 보러가기](주소) |
| **3D UI** <br> [코드 보러가기](주소) | **이벤트 카메라** <br> [코드 보러가기](주소) | **태그 메시 비활성화** <br> [코드 보러가기](주소) |
| **런타임 데이터 반영** <br> [코드 보러가기](주소) | **소켓 시스템** <br> [코드 보러가기](주소) | **Object Pool** <br> [코드 보러가기](주소)  |



