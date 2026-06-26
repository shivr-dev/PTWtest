# PTW 2027 Browser Secure v17

## PWA install prompt improvements

- The install prompt now detects three states:
  - Directly installable
  - Manual install required
  - Probably already installed / Chrome blocked duplicate installation
- If Chrome has already installed the PWA and refuses to prompt again, the UI now explains that clearly instead of showing a broken install button.
- The floating install button has moved away from the bottom-right exam controls.
- The install prompt automatically hides on Exam Prep and Exam Room pages so it will not block questions, answer options, highlighter, recording, or navigation.
- Added guidance for the case where Chrome says the app is installed but no desktop icon appears: uninstall old PTW from Android Settings → Apps, then add it again.
- Version upgraded to v17.0.0.
