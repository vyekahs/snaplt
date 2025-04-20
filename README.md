# snaplt - macOS 창 관리 애플리케이션

snaplt은 macOS 창 관리 애플리케이션으로, 마우스를 사용하지 않고도 키보드 단축키나 메뉴바를 통해 쉽고 빠르게 창을 배치할 수 있습니다.

## 웹사이트

[https://사용자명.github.io/snaplt](https://사용자명.github.io/snaplt)

## 주요 기능

- 다양한 레이아웃 (전체화면, 반분할, 1/4분할, 1/3분할, 2/3분할 등)
- 키보드 단축키
- 멀티 모니터 지원
- 직관적인 메뉴바
- 사용자 설정 가능
- 레이아웃 반복 적용

## 설치 방법

웹사이트에서 snaplt.zip 파일을 다운로드하여 설치하세요.

## Overview
The snaplt project is a macOS application designed for efficient window management. It allows users to control the positioning and sizing of application windows using keyboard shortcuts and a menu bar interface. The application leverages macOS accessibility features to detect and manipulate window states across multiple monitors.

## Features
- **Current Window Detection and Control**: Detects the currently active window and allows users to adjust its position and size.
- **Screen Alignment**: Provides options to align windows to predefined layouts, including full screen, split views, and quadrants.
- **Multi-Monitor Support**: Recognizes all connected monitors and adjusts window layouts based on the active monitor.
- **Keyboard Shortcuts**: Supports global keyboard shortcuts for quick window management.
- **Menu Bar Interface**: Offers a user-friendly menu bar for easy access to window management options.
- **Preferences Management**: Allows users to customize keyboard shortcuts and application settings.
- **Accessibility Permissions**: Requests necessary accessibility permissions to control windows.

## Project Structure
- **Application**: Contains the main application files, including the entry point and app delegate.
- **Views**: Defines the user interface components, including the main content view and menu bar.
- **Models**: Manages data structures for window layouts and user preferences.
- **Services**: Implements core functionalities such as window management, accessibility checks, and shortcut handling.
- **Utils**: Provides utility functions and constants used throughout the application.
- **Resources**: Contains image assets and other resources.
- **Helpers**: Includes helper functions for launching at login and managing accessibility features.
- **Tests**: Contains unit and UI tests to ensure application functionality.

## Setup Instructions
1. Clone the repository to your local machine.
2. Open the `snaplt.xcodeproj` file in Xcode.
3. Build and run the project to test the application.

## Usage Guidelines
- Use the menu bar icon to access window management options.
- Customize keyboard shortcuts in the preferences view.
- Ensure accessibility permissions are granted for full functionality.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.