VELA — SMART WHEELCHAIR WEBSITE

CONTENTS
- index.html: Complete responsive website, voice recognition, virtual wheelchair animation,
  command history, simulation mode, and optional ESP32 serial connection.

HOW TO RUN WITHOUT ESP32
1. Extract this ZIP file.
2. Open index.html in Google Chrome or Microsoft Edge.
3. Click "Start simulation" (simulation mode is enabled by default).
4. Use the arrow buttons and STOP to test movement states and wheelchair animations.
5. Click the microphone and allow microphone access to test voice commands.

VOICE COMMANDS
- Forward
- Backward
- Left
- Right
- Stop

OPTIONAL ESP32 CONNECTION
- Connect ESP32 to the computer with USB.
- Use a recent Chrome or Edge browser in a secure context (localhost or HTTPS).
- Click "Connect ESP32" and select the serial port.
- The page sends newline-terminated text commands at 115200 baud:
  FORWARD, BACKWARD, LEFT, RIGHT, STOP
- Your ESP32 firmware must read these commands and implement the matching motor control.

IMPORTANT SAFETY INFORMATION
This is a visual/software demonstration, not a certified wheelchair controller.
The illustrated wheelchair is only an interface animation; no real vehicle is simulated physically.
Do not connect this prototype directly to a person-carrying wheelchair without independent
hardware safety design, a physical emergency stop, communication-loss fail-safe, current limiting,
mechanical safeguards, and qualified testing. First test with wheels lifted and motor power isolated.
Speech recognition support varies by browser and may use an online service.
