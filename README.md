# Babbar

식단표 정보를 macOS 메뉴바와 Windows 작업 표시줄에서 바로 확인하는 위젯입니다.

## 화면

<table>
  <tr>
    <th width="50%">macOS</th>
    <th width="50%">Windows</th>
  </tr>
  <tr>
    <td valign="top"><a href="assets/screenshot-macos.png"><img src="assets/screenshot-macos.png" alt="Babbar macOS 메뉴바 식단표" width="100%"></a></td>
    <td valign="top"><a href="assets/screenshot-windows.png"><img src="assets/screenshot-windows.png" alt="Babbar Windows 작업 표시줄 식단표" width="100%"></a></td>
  </tr>
</table>

## 요구 사항

- macOS 26 이상, Apple Silicon
- Windows 10 또는 11 (x64)

## 설치

### macOS

- [Releases](https://github.com/beaulowo/Babbar/releases/latest)에서 dmg 파일을 받은 뒤 `Babbar.app`을 `Applications`로 드래그.
- "‘Babbar.app’을(를) 열지 않음" 팝업이 나타나면 설정 - 개인정보 및 보안 - 그래도 열기 클릭

### Windows

<a href="https://apps.microsoft.com/detail/9NG9HX7J8JCT?mode=direct"><img src="https://get.microsoft.com/images/ko%20dark.svg" alt="Microsoft Store에서 받기" width="200"></a>

- Microsoft Store에서 설치하는 것을 권장합니다. 업데이트도 Microsoft Store가 자동으로 설치합니다.
- Microsoft Store를 쓸 수 없다면 [Releases](https://github.com/beaulowo/Babbar/releases/latest)에서 `windows-x64-setup.exe` 파일을 받아 실행하세요. "Windows의 PC 보호" 창이 나타나면 추가 정보 - 실행을 누르면 됩니다.
- 두 방식을 함께 설치하면 작업 표시줄에 아이콘이 두 개 생깁니다. exe로 설치한 앱을 지운 뒤 Microsoft Store 버전을 설치하세요.

## 사용

### macOS

- 메뉴바의 Babbar 아이콘을 누르면 현재 시각 기준 식단표가 표시됩니다.
- 식사 시간이 지나면 다음 식단표로 자동 전환됩니다.
- 설정 버튼에서 로그인 시 자동 실행을 켤 수 있습니다.
- 설정 버튼에서 업데이트를 확인할 수 있습니다.

### Windows

- 작업 표시줄 오른쪽의 Babbar 아이콘을 누르면 현재 시각 기준 식단표가 표시됩니다. 아이콘이 보이지 않으면 `^`를 눌러 숨겨진 아이콘에서 찾을 수 있습니다.
- 식사 시간이 지나면 다음 식단표로 자동 전환됩니다.
- 설정 버튼에서 Windows 시작 시 자동 실행을 켤 수 있습니다.
- exe로 설치했다면 설정 버튼에서 업데이트 확인과 업데이트 자동 설치를 사용할 수 있습니다.

## 라이선스

GPL-2.0
