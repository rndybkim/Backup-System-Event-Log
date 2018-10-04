# Backup-System-Event-Log

이 프로젝트는 Windows 기반의 OS 에서 Event Viewer로 볼 수 있는 .evtx 파일을 System 폴더로부터 백업 받아오는 프로젝트이다.

개발환경
OS : Windows 10
IDE : Visual Studio 2008 SP1
Language : C#(WPF)

이 프로젝트는 C:\\Windows\\System32\\winevt\\Log 폴더의 이벤트 로그 파일 3종류를 실행파일 위치에 복사한다.

복사되는 파일은 아래와 같다.

1. Application.evtx
2. System.evtx
3. HardwareEvents.evtx 

