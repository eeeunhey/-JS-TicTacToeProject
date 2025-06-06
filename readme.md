🔧 프로젝트 개요
목표: 두 명의 플레이어가 번갈아가며 플레이하는 TicTacToc 게임 구현
주요 구현 요소: HTML, CSS, JavaScript

📌 주요 기능 및 구현 순서

1. 플레이어 설정 기능
플레이어 이름을 입력할 수 있는 입력 양식 (Form) 구성
입력 양식은 오버레이 모달(overlay modal) 형태로 표시됨

2. 게임 시작 버튼 기능
{Start Game} 버튼 클릭 시:
이전 게임 기록이 있을 경우 게임 보드 초기화
“Game Over” 메시지가 있으면 해당 메시지도 제거

3. 턴제 게임 플레이 기능
두 명의 플레이어가 번갈아 가며 차례를 가짐
각 턴에서 플레이어의 기호(예: X, O) 표시

4. 게임 로직 처리
클릭된 각 필드에 대해:
어떤 플레이어가 선택했는지 추적
매 턴 후 승리 조건 또는 무승부 조건 체크

5. 게임 종료 처리
{Game Over} 메시지 표시
무승부일 경우: 무승부 알림
승리자 발생 시: 승리자 강조

🎯 마일스톤 프로젝트 To-Do 리스트

1. 🧑‍💻 플레이어 설정 기능
 [ ]플레이어 이름 입력 양식 UI 만들기 (오버레이 모달)
 [ ]입력값 유효성 검사 (빈 값 확인)
 [ ]이름 유효할 경우 → 플레이어 이름 갱신 및 저장

2. 🕹️ 게임 시작 기능
 [ ]{Start Game} 버튼 기능 구현
 [ ]이전 게임 보드 상태 초기화
 [ ]"Game Over" 메시지 제거 처리

3. 🔄 턴제 게임 플레이
 [ ]현재 턴 상태 추적 기능 구현
 [ ]클릭한 필드에 플레이어 기호 표시
 [ ]플레이어가 번갈아가며 턴 수행

4. 🧠 게임 로직 처리
 [ ]클릭된 필드마다 소유자 추적
 [ ]승리 조건 확인 (3개 일치 등)
 [ ]무승부 조건 확인 (모든 칸 사용 시)

5. 🏁 게임 종료 처리
 [ ]승리자 또는 무승부 메시지 출력
 [ ]{Game Over} 화면 표시
 [ ]승리자 강조 (스타일 적용)
