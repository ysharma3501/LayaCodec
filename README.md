# LayaCodec
A highly efficient neural audio codec for TTS models

code
```
from IPython.display import Audio
import torch
file = "audio_path"
with torch.no_grad():
    codes = model.encode_audio(file)
    wav = model.decode_codes(codes)
```
