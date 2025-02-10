# mpv_smooth
Playback smooth video with frame interpolation on mpv

## **Installation**
1. Install VapourSynth portable version. Get .bat and .ps1 files from [releases](https://github.com/vapoursynth/vapoursynth/releases) and run it.
2. Copy these files to mpv folder
3. Copy **vs-plugins** to mpv folder
4. Copy **k7sfunc.py** from [MPV_lazy](https://github.com/hooke007/MPV_lazy)
5. Add the function to **mpv.conf** or **input.conf**

## **Input.conf**
```conf
!                 vf set vapoursynth="~~/vs/MEMC_MVT_LQ.vpy"
@                 vf set vapoursynth="~~/vs/MEMC_MVT_STD.vpy"
SHARP             vf set vapoursynth="~~/vs/MEMC_RIFE_STD.vpy"
```

## **Notes** 
If you need specific filter, get from [MPV_lazy](https://github.com/hooke007/MPV_lazy/tree/main/portable_config/vs)
