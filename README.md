# RobotSample
## 1.디렉토리 구조

├─app 비즈니스 코드
│  ├─robotos  
│  │  ├─application 프로그램 구성
│  │  │	    ├─ ModuleCallback.java CoreService 계층의 기본 콜백 인터페이스 가져오기
│  │  │     ├─ RobotOSApplication.java CoreService 연결 및 음성 초기화에 사용되는 현재 애플리케이션 항목
│  │  │     ├─ SpeechCallback.java 음성 SkillApi 콜백 인터페이스 가져오기
│  │  ├─fragment 비즈니스 시나리오
│  │  │     ├─ BaseFragment.java 기본 비즈니스 시나리오 구성, 공용 구성 요소 로드
│  │  │     ├─ ChargeFragment.java 충전 비즈니스 모듈
│  │  │     ├─ LeadFragment.java 리드 비즈니스 모듈
│  │  │     ├─ LocationFragment.java 위치 관련 모듈
│  │  │     ├─ MainFragment.java 모듈 시작 위치
│  │  │     ├─ NavigationFragment.java 네비게이션 비즈니스 모듈
│  │  │     ├─ SpeechFragment.java 음성 서비스 모듈
│  │  │     ├─ SportFragment.java 기본 스포츠 비즈니스 모듈
│  │  │     ├─ VisionFragment.java 비전 비즈니스 모듈
│  │  ├─ view 공개 구성요소
│  │  │     ├─ BackView.java 반환 제어
│  │  │     ├─ ResultView.java 결과 표시 제어
│  │  ├─ LogTools.java 로그 수집 도구
│  │  ├─ MainActivity.java 앱 메인 페이지 항목
│  ├─ res 리소스 디렉토리
│  ├─AndroidManifest.xml 앱 매니페스트 파일
│

## 2. 环境配置
机器人应用的开发需要依赖Android开发环境,IDE工具，详细配置请参考以下文档。
Android开发环境
### 2.1 Android开发环境
机器人系统是基于Android定制开发，所以我们在开发机器人应用的时候需要配置Android开发环境，具体Android开发环境配置，请参考 : https://developer.android.com/ 。
