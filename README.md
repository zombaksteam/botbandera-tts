# botbandera-tts
BotBandera TTS

## Config example
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

3. Go to `C:\tts\` directory, run `tts.exe` wait untill application will be loaded and allow access to network:
![firewall.png](firewall.png?raw=true "firewall.png")
