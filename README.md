# 🥁 Ultra-Reactive 60 BPM Metronome

Ultra-fast web metronome with instant startup in 100-200ms.

## 🎵 Features

- **TICK** high-pitched on the 1st beat of each measure
- **tock tock tock** low-pitched on beats 2, 3, 4
- Golden animation to mark the first beat
- Instant startup with no latency
- iPhone compatible with automatic shortcut

## 🚀 iPhone Shortcut (Auto Start/Stop)

### Setup Instructions:

1. **Open the "Shortcuts" app** on iPhone
2. **Tap "+"** (new shortcut)
3. **Search for "Open URL"** and add this action
4. **Paste this URL**:
   ```
   https://YOURUSERNAME.github.io/metronome-60bpm/?autostart=true
   ```
5. **Name it "Metronome"** and save
6. **Add to home screen** via shortcut options

### Usage:
- **1 tap** = Starts the metronome
- **1 more tap** = Stops it automatically
- **Works even if Safari is closed**

## ⚡ Technical Optimizations

- Pre-loaded audio with activated context
- "Warmed up" audio pipeline to eliminate latency
- Immediate execution without setTimeout
- Optimized frequencies for authentic wood sound

## 🎯 How to Use

1. **Open the page** in Safari on iPhone
2. **Test** with the big green "START" button
3. **Create the shortcut** with the `?autostart=true` URL
4. **Enjoy** instant metronome access!

## 🔧 Development

Built with HTML/JavaScript using Web Audio API for minimal latency. Compatible with all modern browsers.

---

*The first TICK is higher-pitched and louder to clearly mark the beginning of each measure, exactly like a real mechanical metronome.*