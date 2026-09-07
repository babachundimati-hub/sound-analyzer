# 🎛️ Sound Analyzer AI
> **Professional-grade, client-side acoustic signal analysis and real-time audio engineering suite in the browser.**
[![Website](https://img.shields.io/badge/Live_Demo-soundanalyzerai.com-06b6d4?style=for-the-badge&logo=googlechrome&logoColor=white)](https://soundanalyzerai.com)
[![Framework](https://img.shields.io/badge/Framework-Astro_v5-f97316?style=for-the-badge&logo=astro&logoColor=white)](https://astro.build)
[![Styling](https://img.shields.io/badge/Styling-Tailwind_v4-38bdf8?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![Privacy](https://img.shields.io/badge/Privacy-100%25_Client--Side-10b981?style=for-the-badge)](https://soundanalyzerai.com)
**[Sound Analyzer AI](https://soundanalyzerai.com)** brings studio-grade audio testing, frequency visualization, and acoustic analysis straight to modern browsers. Built with the native Web Audio API, Canvas 2D, and WebGL, it processes audio with zero cloud transmission and zero latency.

<img width="1469" height="806" alt="soundanalyzerai" src="https://github.com/user-attachments/assets/b61f5349-18e8-4b55-8290-cb8ec0734189" />

---
## 🚀 Key Features & Audio Tools
* 📊 **[Real-Time Spectrum Visualizer](https://soundanalyzerai.com/)**: Multi-mode visualizer supporting Oscilloscope, Logarithmic FFT Spectrum, Circular Waveform, and 3D Particle Cloud.
* 🔊 **[Tone Generator & Synthesizer](https://soundanalyzerai.com/tools/tone-generator)**: Multi-wave oscillator (Sine, Square, Triangle, Sawtooth), binaural beats, frequency sweeps, and acoustic calibration presets.
* 🎸 **[Audio Pitch Detector](https://soundanalyzerai.com/tools/audio-pitch-detector)**: Sub-cent musical instrument tuner powered by autocorrelation (YIN) and parabolic interpolation.
* 📉 **[Leq Sound Level Meter](https://soundanalyzerai.com/tools/leq-noise-meter)**: Continuous equivalent sound levels (LAeq, LCeq, LZeq) with OSHA and WHO noise risk monitoring.
* ⚡ **[Mains Hum & Ground Loop Detector](https://soundanalyzerai.com/tools/mains-hum-detector)**: 50Hz/60Hz electrical interference diagnostic tool with harmonic distortion breakdown.
* 🎚️ **[DSP Filter Sandbox](https://soundanalyzerai.com/tools/dsp-filter-sandbox)**: Interactive biquad digital filter laboratory with live real-time Bode plot response.
---
## ⚡ Tech Stack
* **Core**: [Astro](https://astro.build) (Static Site Generation)
* **Styling**: [Tailwind CSS v4](https://tailwindcss.com) via `@tailwindcss/vite`
* **DSP Engine**: Native Web Audio API (`AudioContext`, `AnalyserNode`, `BiquadFilterNode`)
* **Graphics**: HTML5 Canvas 2D & WebGL
* **Hosting**: Cloudflare Pages
---
## 🔒 Privacy Architecture
Sound Analyzer AI executes 100% inside your client browser. No microphone audio or file upload data is ever transmitted, recorded, or stored on external servers.
---
## 💻 Local Development
```sh
git clone https://github.com/your-username/sound_analyzer.git
cd sound_analyzer
npm install
npm run dev
