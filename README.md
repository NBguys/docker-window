윈도우에 도커 설치
Hyper-V 활성화
관리자 권한으로 PowerShell을 열고(실행 파일 "관리자 권한으로 실행"을 마우스 오른쪽 버튼으로 클릭) 다음을 실행합니다.
다음 명령: 
```
Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V -All
```

컨테이너 기능 활성화
관리자 권한으로 PowerShell을 열고(실행 파일 "관리자 권한으로 실행"을 마우스 오른쪽 버튼으로 클릭) 다음을 실행합니다.
다음 명령:
```
Enable-WindowsOptionalFeature -Online -FeatureName containers –All
```

