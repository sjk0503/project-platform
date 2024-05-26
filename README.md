# project-platform
## 프로젝트 목표
프로젝트의 목표는 학우들의 팀프로젝트 진행을 위해 팀 구성에 있어 효율성을 증대 시키는 것입니다. <br/>
또한 실제 수업에서 배운 이론들을 프로젝트에 적용함으로써 실제 업무와의 차이를 느끼고 싶었고, 학교에서 배우지 않은 것들도 스스로 학습하며 지식을 넓혀보고 싶습니다. <br/>
최종 목표 결과물인 어플리케이션을 구축하면서 부딫히는 어려움을 겪으며 부족함을 느끼고 채우는 것이 목표입니다. <br/>

## 설계도
<img width="800" alt="스크린샷 2023-12-16 오후 5 32 07" src="https://github.com/sjk0503/project-platform/assets/108213769/dc0f9503-9183-4684-8538-b501c33683e4">

실제로 구현한 어플리케이션은 Xcode와 SwiftUI를 통해 개발되었고, AWS 클 라우드 서비스를 통해 서버가 구축되었습니다. <br/>
어플리케이션은 데이터베이스와 통신을 위해 API Gateway가 사용됩니다. <br/>
어플리케이션은 API Gateway 를 호출하고, API Gateway는 Lambda 함수를 호출하게 됩니다. <br/>
Lambda 함수는 RDS를 직접적으로 컨트롤하게되며 요청한 데이터는 다시 Lambda 함수에서 API Gateway로, API Gateway에서 어플리케이션으로 이동합니다. <br/>


## 결과물 및 UI
### 기능
구현한 어플리케이션의 다양한 기능들이 있지만 프로젝트의 목표인, 팀 구성을 하는 방식은 프로젝트 추천을 통해 팀이 결성됩니다. <br/>
프로젝트 추천을 위해선 이전에 사용자가 참여했던 프로젝트를 수기로 입력합니다. <br/>
수기로 입력한 프로젝트를 기준으로 현재 모집 중인 프로젝트들 중 유사한 프로젝트의 리스트를 보여주고 사용자는 원하는 프로젝트를 선택해 참여하게 됩니다. <br/>
기존 목표인 자동 팀 결성 서비스는 사용자가 원치않은 방식으로 팀이 구성될 가능성이 존재함에따라 사용자가 선택적으로 팀을 선택할 수 있는 방식으로 변경되었습니다. <br/>

### 로그인
<img src="https://github.com/sjk0503/project-platform/assets/108213769/6bc83265-1102-4e25-a1b9-4b7965cbf1ba" width="200" height="400"/>

### 회원가입
<img src="https://github.com/sjk0503/project-platform/assets/108213769/54bf91b3-7f64-4487-9154-6d1b0e640f6e" width="200" height="400"/>

### 탭1
<img src="https://github.com/sjk0503/project-platform/assets/108213769/3a0345e9-fc39-4209-a362-7fe303da1e40" width="200" height="400"/>
<img src="https://github.com/sjk0503/project-platform/assets/108213769/cea4f1dd-ee6c-4ff1-9470-c64b445277e1" width="200" height="400"/>

### 탭2
<img src="https://github.com/sjk0503/project-platform/assets/108213769/42285fd0-f715-4712-a2cd-7655c2fd6747" width="200" height="400"/>
<img src="https://github.com/sjk0503/project-platform/assets/108213769/c2584d48-0be1-40f0-93a8-0c5350693814" width="200" height="400"/>

### 탭3
<img src="https://github.com/sjk0503/project-platform/assets/108213769/a9eae5ba-e6eb-4639-ae56-342a17808d7a" width="200" height="400"/>
<img src="https://github.com/sjk0503/project-platform/assets/108213769/f20f7316-78c3-4a74-8c2c-35216b8083c8" width="200" height="400"/>
<img src="https://github.com/sjk0503/project-platform/assets/108213769/08125057-8831-4af4-a9ba-7dbbf406a0ae" width="200" height="400"/>

### 탭4
<img src="https://github.com/sjk0503/project-platform/assets/108213769/c5194c7e-d06e-4308-85c1-0b3bc361ea5e" width="200" height="400"/>
<img src="https://github.com/sjk0503/project-platform/assets/108213769/3fb2f3b2-6d27-414b-9665-d5ca09b9836f" width="200" height="400"/>
<img src="https://github.com/sjk0503/project-platform/assets/108213769/92b4675d-b974-47bc-a9a9-90c8819aa0f8" width="200" height="400"/>

### 탭5
<img src="https://github.com/sjk0503/project-platform/assets/108213769/bb089de9-c068-4859-a30e-5ad8e07be2c3" width="200" height="400"/>
