# virtual-performance-ai
가상공연 구축을 위한 AI 기술 키워드 및 AI 요소기술 관련 최신 논문, 예제를 포함한 연구 자료

# Virtual Performance AI Repository

This repository provides:
- **AI technology keywords** related to virtual performance construction.
- **Research papers** categorized by technology keywords.
- **Example implementations** to demonstrate AI applications.

## Repository Structure
- `keywords/`: Contains AI technology keywords and descriptions.
- `papers/`: Organized research papers for each keyword.
- `examples/`: Code examples showcasing practical implementations.
- `tools/`: Scripts for fetching papers and managing data.



## 🌄 &nbsp;AI 기술논문 및 예제를 공유할 수 있습니다!
<details>
  <summary>나만의 <code>프로젝트</code>을 만들어 <code>AI 요소기술 예제</code>을 공유하세요.</summary>
  <img src="./docs/주요기능/콜렉션/1.gif" width=100%>
</details>
<details>
  <summary>마음에 든 프로젝트 예제에 하트를 눌러 <code>좋아요</code>를 표현하세요.</summary>
  <img src="./docs/주요기능/콜렉션/2.gif" width=100%>
</details>

<br>

## 🏞 &nbsp;기술키워드 추천 기능을 이용해보세요!
<details>
  <summary>가상공연 구축 <code>기술키워드</code> 검색을 통해 비슷한 AI 요소기술을 추천해줍니다.</summary>
  <img src="./docs/주요기능/콜렉션/3.gif" width=100%>
</details>

<br>

## 🌃 &nbsp;저랑 같이 AI요소기술 연구하러 갈래요?
<details>
  <summary><code>모임</code>을 만들어 같이 AI요소기술을 연구할 동료를 구할 수 있습니다.</summary>
  <img src="./docs/주요기능/같이연구해요/1.gif" width=100%>
</details>
<details>
  <summary>주최자가 모집 마감 버튼을 누르면 <code>채팅</code> 메뉴에서 참여자들끼리 대화할 수 있습니다.</summary>
  <img src="./docs/주요기능/같이연구해요/2.gif" width=100%>
  <img src="./docs/주요기능/같이연구해요/3.gif" width=100%>
</details>

<br>
<br>

## 👀 &nbsp;자, 이제 준비 됐나요? `가상공연 구축 AI요소기술을 찾기 위한 기술키워드`을 직접 검색해보세요!

[📷 MR미디어랩 사이트로 이동하기](https://blog.naver.com/mr_media_lab)   




### ✨ 가상공연 구축을 위한 첫 AI 요소기술 정리! (2024.12.12.)

가상공연 구축을 위한 구성요소별 요구조건에 따른 기술키워드, AI 요소기술, 관련 AI기술논문 예시를 포함한다. 😊

</br>

## '가상객체' 구성요소의 기술키워드 및 AI 요소기술 

| **대분류**       | **중분류**             | **소분류**         | **요구조건**                                                                                                                                     | **기술키워드**                                              | **하위 AI 요소 기술**                                      |
|-------------------|------------------------|--------------------|------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------|-----------------------------------------------------------|
| **가상객체**     | 공연자 가상 아바타      | 움직임 표현        | 공연자의 신체 동작을 실시간으로 추적하고 가상 아바타에 자연스럽고 정확하게 현실감을 반영할 수 있어야 한다.                                         | Human Pose Estimation and Rendering                      | 포즈추정을 위한 특징 추출 강화, 2D 포즈로부터 정확한 3D 골격 추정, 가림 및 혼잡한 환경 처리           |
|                   |                        |                    |                                                                                                                                                 | Human Animation                                           | 애니메이션의 시간적 일관성 유지, 애니메이션의 모션 전송의 정확성 향상, 인간과 카메라 움직임 동시 관리    |
|                   |                        |                    |                                                                                                                                                 | Animatable human body model                              | 관찰된 데이터와 정준 데이터 간의 정확한 대응 생성, 신체 형태에 맞춘 스키닝 가중치 생성, 움직임과 표면 질감 복제의 정밀 구현|
|                   |                        | 표정 표현          | 공연자의 얼굴 표정을 정밀하게 인식하고 아바타에 즉각적으로 정확성과 자연스러움을 반영할 수 있어야 한다.                                           | Facial Expression Recognition through Feature Point Tracking | 얼굴 랜드마크의 추적 및 모니터링을 통한 미세 표정 분석, 랜드마크 변화 매핑을 통한 복잡한 표정의 효과적 포착, 재매개된 특징 융합(Re-parameterized Feature Fusion)|
|                   |                        |                    |                                                                                                                                                 | Facial Feature Analysis                                   | 실시간 얼굴 감정 분석, 다양한 얼굴 특징과 문화적 감정 분석, 깜빡임 빈도와 시선 분석|
|                   |                        |                    |                                                                                                                                                 | Facial Animation Generation Techniques                   | 키포인트 기반 애니메이션 모델, 다중 모달 디퓨전 모델, 얼굴 움직임 동기화     |
|                   |                        | 음성 표현          | 실시간 음성 전달과 감정이 포함된 자연스러운 음성 합성을 통해 아바타가 공연자의 음성을 정확하게 표현할 수 있어야 한다.                               | Speech Emotion Recognition                                | 말의 톤과 피치 변화 포착, 시간적 의존성 포착, 복잡한 음성 패턴 포착, 오디오와 기타 데이터 유형 통합    |
|                   |                        |                    |                                                                                                                                                 | Emotion-based voice-gesture generation                   | 오디오에서 감정적이고 리드미컬한 특징 추출, 다인 환경에서의 대화 맥락을 고려한 제스처 생성  |
|                   | 관객 가상 아바타       | 아바타 생성        | 사용자가 간편하게 자신이 원하는 내/외적인 성격과 특성이 표상될 수 있도록 외형과 의상 및 액세서리 표현 등을 조합하여 손쉽게 만들 수 있어야 한다.       | 3D Human Avatar Generation Technology                    | 2D 이미지로 3D 아바타 변환, 텍스트/이미지로 포즈와 체형 조정 및 실시간 아바타 생성, 층별 아바타 생성, 신체 일관성 유지하며 의상 전송|
|                   |                        |                    |                                                                                                                                                 | 3D Human Avatar Modeling                                 | 단일 RGB 이미지로 상세한 전신 아바타 생성, 텍스쳐와 지오메트리의 3D 일관성 유지, 얼굴과 손 표현을 포함한 신체 전체의 역학 캡쳐       |
|                   |                        | 감정 표현          | 관객의 감정변화를 효과적으로 표현할 수 있도록 감지하거나 선택된 감정 상태를 반영해야 한다.                                                        | Multimodal Emotion Recognition                           | 모달리티 전반의 정보 통합, 추출된 특징을 적응형 증류 통해 효과적으로 융합, 음성과 비디오 데이터에서 특징 소실 방지    |
|                   |                        |                    |                                                                                                                                                 | Emotion-aware Adaptation                                 | 감정의 다중 수준 카테고리 분류, 감정 간 클러스터 분리, 클러스터 내 감정 일관성 증진 |
|                   |                        | 움직임 추적        | 센서 및 영상 기반으로 사용자의 신체 움직임을 정밀하게 추적하고 가상 아바타에 반영할 수 있어야 한다.                                                | 3D Facial Animation Transfer                             | 지오메트리와 텍스쳐의 이중 분리 스타일 가이드 메커니즘, 음성 신호와 립싱크 동기화, 현실적인 얼굴 움직임 구현 및 얼굴 표현 조작 |
|                   |                        |                    |                                                                                                                                                 | Human 3D Pose Estimation                                 | 가림(occlusion)과 자세 변화 및 여러 인물의 상호작용을 위한 공간 정보의 동적 처리, 외부 데이터 이상치에 민감하지 않는 관절 위치 추정, 동적 환경에서의 행동 인식 및 추적|
|                   |                        |                    |                                                                                                                                                 | 3D Facial Modeling                                       | 사진에서 내부 얼굴 구조 추정, 표정 및 나이 등의 다양한 얼굴 특징으로 세밀한 디테일 조정, 단일 이미지를 기반으로 한 3D 복원 |
|                   | 가상 공연장 객체       | 그래픽 객체        | 가상 공연장 내 그래픽 객체는 연출가의 의도에 부합하도록 다양한 각도와 거리에서도 일관성을 유지해야 한다.                                            | Physics Based Simulation                                 | 단일 이벤트 효과 메커니즘 예측, 유체 역학 및 변형 가능 물체의 복잡한 행동에 대한 실시간 처리            |
|                   |                        |                    |                                                                                                                                                 | world model 기술 world model technology                  | 단일 패스로 전체 정책 궤적(on-policy trajectory)을 생성, 이미지 시퀀스의 압축과 예측, 다중 소스 데이터 융합, 포인트 클라우드 필터링 및 모델 조정      |
|                   |                        |                    |                                                                                                                                                 | Neural Rendering                                          | 불투명한 버퍼와 투명 버퍼 분리, 과학적 시뮬레이션에서 생성된 포인트 클라우드 데이터 처리, 메모리 요구사항을 줄이는 양자화, 에너지 효율적 렌더링|
|                   |                        |                    |                                                                                                                                                 | Optimization of Real time Ray Tracing                   | GPU 병렬 처리, 계층적 데이터 구조, 선택적 샘플링|
|                   | 조명                   |                   | 공연장의 분위기와 감정선을 강조하는 다이나믹한 조명 효과를 지원해야 한다.                                                                     | Stage Lighting Simulation                                | 복잡한 조명 구성의 접근성, 방향성 조명의 효율적 시뮬레이션|
|                   |                        |                   |                                                                                                                                                 | Real-time Global Illumination                            | 안정적이고 효율적인 광 필드 렌더링,정교한 표면을 위한 높이 기울기 분석, 그림자와 주변 폐색(ambient occlusion) 계산        |
|                   | 가상 카메라            |                   | 다양한 시점에서 실감 있는 시각적 경험을 제공하고 자유로운 카메라 이동 및 초점 조절을 지원해야 한다.                                                 | Neural Rendering for Cinematic                          | 순열 불변 투명성 렌더링, 복잡한 글로벌 일루미네이션 효과 처리, 자유시점 비디오와 동적 배경의 효율적 렌더링|

---
