# QuestToolkit Activator (퀘스트툴킷 액티베이터)

> **[EN] Important: If QuestToolKit's internal ADB activation fails, you can use this app to activate ADB first, and then proceed with QuestToolKit.**
>
> **[KR] 중요: 퀘스트툴킷에서 자체적으로 ADB 활성화가 되지 않을 경우, 이 앱을 통해 ADB를 먼저 활성화한 후 퀘스트툴킷의 기능을 정상적으로 이용할 수 있습니다.**

---

## Description (설명)
**[EN]** This application is designed to activate Wireless ADB on Quest devices, **regular Android smartphones, and Galaxy XR devices**. It provides essential utilities such as VPN connectivity, an ADB command executor, and automatic APK installation, simplifying the process of setting up and maintaining your Android-based environment.

**[KR]** 이 애플리케이션은 퀘스트 기기뿐만 아니라 **일반 안드로이드 휴대폰 및 갤럭시 XR 기기**에서도 무선 ADB를 활성화하도록 설계되었습니다. VPN 연결, ADB 명령어 실행기, 자동 APK 설치와 같은 필수 유틸리티를 제공하여 안드로이드 기반 환경의 설정 및 유지 과정을 단순화합니다.

---

## Features (주요 기능)
*   **Wireless ADB Activation**: Easily enable wireless debugging for seamless device management across Quest, smartphones, and XR devices. (무선 ADB 활성화: 퀘스트, 스마트폰, XR 기기 등 다양한 장치의 원활한 관리를 위해 무선 디버깅을 쉽게 활성화합니다.)
*   **ADB Command Executor**: Execute custom `adb` and `adb shell` commands directly from the app's UI. (ADB 명령어 실행기: 앱의 UI에서 직접 `adb` 및 `adb shell` 명령어를 실행합니다.)
*   **VPN Support**: Integrated OpenVPN functionality for secure and unrestricted access. (VPN 지원: 안전하고 제한 없는 액세스를 위한 OpenVPN 기능 통합.)
*   **Auto APK Installer**: Download and install the latest QuestToolKit APK directly within the app. (자동 APK 인스톨러: 앱 내에서 최신 퀘스트툴킷 APK를 직접 다운로드하고 설치합니다.)
*   **Permission Manager**: Automatically grant necessary system permissions via ADB. (권한 관리자: ADB를 통해 필요한 시스템 권한을 자동으로 부여합니다.)

---

## ADB Activation Guide (ADB 활성화 가이드)

### [English]
1.  **Connect to PC**: Connect your device (Quest, Smartphone, or Galaxy XR) to your PC via a USB cable.
2.  **Enable Wireless Debugging**: Run the command `adb tcpip 5555` on your PC. (*Android SDK Platform-Tools must be installed on your PC.*)
3.  **Always Allow Debugging**: Restart the app on your device and select "**Always allow from this computer**" when the debugging prompt appears.
4.  **Re-activation**: If the device reboots, running this app again will automatically reactivate ADB.

### [한국어]
1.  **PC 연결**: USB 케이블을 사용하여 기기(퀘스트, 스마트폰, 갤럭시 XR 등)를 PC에 연결합니다.
2.  **무선디버깅 활성화**: PC에서 `adb tcpip 5555` 명령어를 입력합니다. (*PC에 Android SDK Platform-Tools가 설치되어 있어야 합니다.*)
3.  **디바이스 디버깅 항상 허용**: 앱을 재실행하여 화면에 디버깅 허용 창이 뜨면 "**이 컴퓨터에서 항상 허용**"을 선택합니다.
4.  **재활성화**: 기기가 재부팅되면, 이 앱을 다시 실행하면 자동으로 ADB가 활성화됩니다.

---

## Requirements (요구 사항)
*   Meta Quest Device (Quest 2, Quest 3, Quest Pro)
*   **Galaxy XR Device**
*   **Regular Android Smartphones (Android 10 or higher recommended)**
*   PC with Android SDK Platform-Tools installed.
