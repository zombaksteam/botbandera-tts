# botbandera-tts
BotBandera TTS

## Config
```ini
[TTS]
# Can be "cpu" or "cuda" (CUDA is recommended):
Device: cuda
# From 1 to 10 (for CPU recommended value: 4 and for GPU value: 10):
Threads: 10
# Can be "8000", "24000" or "48000" (bigger value do better quality but takes more resources):
SampleRate: 48000

[WebServer]
# Web server host:
Host: 0.0.0.0
# Web server port:
Port: 8080
```

## Installation
1. Donwload `tts.7z.001`, `tts.7z.002` and `tts.exe` files from latest release here: https://github.com/zombaksteam/botbandera-tts/releases/latest

2. Run `tts.exe` and unpack archive to disk `C:\`

3. Go to `C:\tts\` directory, run `tts.exe` wait until application will be loaded and allow access to network:
![firewall.png](firewall.png?raw=true "firewall.png")

4. Just wait until application will be fully loaded:
![application.png](application.png?raw=true "application.png")

5. TTS ready for use, don't close it, minimize window

For testing/checking purpose, you can navigate in your browser by this link and listen the message: http://127.0.0.1:8080/?user=%D0%B1%D0%B0%D0%BD%D0%B4%D0%B5%D1%80%D0%B0&msg=%D0%B2%D1%81%D0%B5%20%D0%BE%D0%BA
