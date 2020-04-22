ESP32 BT A2DP-SOURCE 
========================

## Summary
ESP32 demo based on ESP-IDF A2DP-SOURCE code. Demo is modified so sink is sourced with music (instead of static) which is stored in music.h header (16bit/44100 sample rate). The demo is not in looping mode. You can specify a BT MAC to skip pairing/discovery mode. 

## BT Security Database
To delete existing BT pair devices, push RESET button and then immediate hold down BOOT button (do not hold down BOOT while pressing reset! that would place the device in download mode.)
  