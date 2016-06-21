# FingerPrintSample

Sample for learning Android fignterprint


## Run on emulator

1. Install Android SDK Tools Revision 24.3, if you have not done so.
2. Enroll a new fingerprint in the emulator by going to **Settings > Security > Fingerprint**, then follow the enrollment instructions.
2. Use an emulator to emulate fingerprint touch events with the following command. 

  **adb -e emu finger touch [finger_id]**
