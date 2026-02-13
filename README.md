# QuestToolkit Activator (퀘스트툴킷 액티베이터)

## Description (설명)
**[EN]** This application is designed to activate Wireless ADB on Quest devices and provide essential utilities such as VPN connectivity and automatic APK installation. It simplifies the process of setting up and maintaining the Quest environment.

**[KR]** 이 애플리케이션은 퀘스트 기기에서 무선 ADB를 활성화하고 VPN 연결 및 자동 APK 설치와 같은 필수 유틸리티를 제공하도록 설계되었습니다. 퀘스트 환경을 설정하고 유지하는 과정을 단순화합니다.

---

## Features (주요 기능)
*   **Wireless ADB Activation**: Easily enable wireless debugging for seamless device management. (무선 ADB 활성화: 원활한 기기 관리를 위해 무선 디버깅을 쉽게 활성화합니다.)
*   **VPN Support**: Integrated OpenVPN functionality for secure and unrestricted access. (VPN 지원: 안전하고 제한 없는 액세스를 위한 OpenVPN 기능 통합.)
*   **Auto APK Installer**: Download and install the latest QuestToolKit APK directly within the app. (자동 APK 인스톨러: 앱 내에서 최신 퀘스트툴킷 APK를 직접 다운로드하고 설치합니다.)
*   **Permission Manager**: Automatically grant necessary system permissions via ADB. (권한 관리자: ADB를 통해 필요한 시스템 권한을 자동으로 부여합니다.)

---

## ADB Activation Guide (ADB 활성화 가이드)

### [English]
1.  **Connect to PC**: Connect your Quest device to your PC via a USB cable.
2.  **Enable Wireless Debugging**: Run the command `adb tcpip 5555` on your PC. (*Android SDK Platform-Tools must be installed on your PC.*)
3.  **Always Allow Debugging**: Restart the app on your Quest and select "**Always allow from this computer**" when the debugging prompt appears.
4.  **Re-activation**: If the device reboots, run this app again to reactivate ADB.

### [한국어]
1.  **PC 연결**: USB 케이블을 사용하여 퀘스트 기기를 PC에 연결합니다.
2.  **무선디버깅 활성화**: PC에서 `adb tcpip 5555` 명령어를 입력합니다. (*PC에 Android SDK Platform-Tools가 설치되어 있어야 합니다.*)
3.  **디바이스 디버깅 항상 허용**: 앱을 재실행하여 화면에 디버깅 허용 창이 뜨면 "**이 컴퓨터에서 항상 허용**"을 선택합니다.
4.  **재활성화**: 기기가 재부팅되면, 이 앱을 다시 실행하여 ADB를 다시 활성화하세요.

---

## Requirements (요구 사항)
*   Meta Quest Device (Quest 2, Quest 3, Quest Pro)
*   PC with Android SDK Platform-Tools installed.
