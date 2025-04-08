![image03](https://github.com/user-attachments/assets/f1cc2ed9-4b29-4158-ac41-16de08cc6ee8)
# 🚀 No Gravity FPS

무중력 공간에서의 자유로운 이동과 VR 핸드트래킹을 활용한 새로운 경험!  
이 프로젝트는 **우주선 배경의 무중력 FPS 게임**으로, **VR 핸드트래킹**과 **바디트래킹**을 통해 현실감 있는 움직임을 구현했습니다.

- 테스트 영상
  https://youtu.be/F8IW01dUCJM

---

## 🎮 주요 특징

- **무중력 이동 구현**:  
  벽을 손으로 밀거나 잡아 이동하며, 반작용 및 회전 로직까지 포함
- **VR 바디 트래킹 리플리케이션**:  
  UE5 + VR Expansion Plugin 기반, 손가락 본 각도까지 공유
- **실시간 멀티플레이 동기화**:  
  모든 플레이어의 위치, 회전, 손 상태 공유
- **직접 제작한 AI 기반 3D 캐릭터 모델**:  
  Leonardo AI + Rodin AI 이용
- **폭탄 / 총기 상호작용 시스템**:  
  커스텀 그랩 로직 + 리플리케이션 + 반동/재장전 이펙트 구현
- **현실감 있는 우주 배경**:  
  직접 구성한 우주선 내부 맵 + 지구/태양 배경

---

## 🛠 개발 환경

- **엔진**: Unreal Engine 5
- **언어**: Blueprint (주로)
- **VR SDK**: VR Expansion Plugin, Meta Movement SDK (부분)
- **기타 툴**: Leonardo AI, Rodin AI

---

## 📽 참고 자료

- 무중력 이동 구현 참고:  
  https://www.youtube.com/watch?v=I9MwdnBoUOI

- 조준 시스템, UI 반동 효과 구현:  
  https://www.youtube.com/watch?v=q6DN0geJjkM&t=113s

- 배경 제작 참고:  
  https://www.youtube.com/watch?v=nxEluE1s3Xk&t=65s

---

## 🌌 스크린샷

![그림01](https://github.com/user-attachments/assets/a1e9b358-1ff1-47e7-a0e6-be71758626a0)
![그림02](https://github.com/user-attachments/assets/4a39829e-6e2b-4cf0-9b07-294e8fd5ded2)
![image01](https://github.com/user-attachments/assets/8d436b16-39ec-4845-848c-90a9b76c61be)
![그림03](https://github.com/user-attachments/assets/7e380057-39e2-4df5-bda5-91d38c1c3fba)

---

## 💡 개발 회고

- **핵심 해결 포인트**
  - 카메라 시점 제한 해제 : 캐릭터 → 폰 전환으로 해결
  - 리플리케이션 시 위치/회전 정보 동기화
  - 커스텀 충돌 및 리스폰 시스템 구현

---

## 📁 실행 방법

> Unreal Engine 프로젝트로 클론 후 실행 가능  
`.uproject` 파일을 오픈하여 확인하세요.

---

보고서 및 발표자료
[2021204042보고서.pdf](https://github.com/user-attachments/files/19650524/2021204042.pdf)


