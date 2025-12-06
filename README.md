<div align="center">

# Aresight Labs
### Real-time Pulse-Doppler Aerospace Radar Engine

**190+ FPS sustained • 32× faster • 9× lower CPU**  
**Pure Python – Zero external dependencies**

Live demo (190 FPS in browser): https://aresight.rosha.ir  
60-second showcase: https://files.catbox.moe/8m9p3k.mp4

<img src="rashidrosha2008.png" alt="Aresight running at 192 FPS" width="100%"/>

</div>

## Features
- Full Range-Doppler map generation in real-time
- Moving Target Indication (MTI)
- Cell-Averaging CFAR detection
- Nuclear-optimized dirty rendering + byte-level diffing
- Runs anywhere Python 3.9+ exists — no pip, no NumPy

## Performance
| Solution              | FPS   | CPU   | Memory | Dependencies |
|-----------------------|-------|-------|--------|--------------|
| Rich/Textual          | 45–65 | ~25%  | 120 MB | 12+ packages |
| Curses-based          | 30–50 | ~18%  | 45 MB  | curses       |
| **Aresight (this)**   | **190+** | **~3%** | **~9 MB** | **None**     |

## Run instantly
```bash
python aresight.py
