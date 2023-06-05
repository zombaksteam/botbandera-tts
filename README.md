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

[BotBandera]
# Your widget URL, take it from BotBandera panel:
WidgetURL: https://botbandera.co.ua/box/v1/XXXXX
```
