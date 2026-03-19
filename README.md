🔊 NoiseGen - Frequency Generator

A clean, browser-based frequency generator built using the Web Audio API for real-time sound synthesis, testing, and experimentation.

NoiseGen • Web Audio • JavaScript

✨ Features
Core Audio Features

🔊 Generate pure sine wave tones in real-time
🎚️ Adjustable frequency control
▶️ Start / Stop playback instantly
⚡ Low-latency audio output

Sound & Control

🎧 Smooth continuous tone generation
📈 Real-time frequency updates without reload
🔇 Immediate stop to prevent unwanted noise

Lightweight Design

⚡ No frameworks or heavy dependencies
🌐 Runs entirely in the browser
📱 Works on desktop and mobile

🧠 Use Cases

🎧 Test headphones, speakers, and audio setups
🧪 Experiment with sound frequencies
🧘 Create focus or meditation tones
📚 Learn how pitch and frequency relate

🚀 Getting Started
Prerequisites

Any modern browser (Chrome, Edge, Firefox)

Installation

Clone the repository:

git clone https://github.com/ogpac69/noisegen.git

Open the project:

cd noisegen
open index.html

Or just open the file manually like it’s 2005 and life was simpler.

🛠️ Technical Stack

JavaScript - Core logic
Web Audio API - Sound generation
HTML - Structure
CSS - Styling

⚙️ How It Works

NoiseGen uses the Web Audio API OscillatorNode to generate sound waves.

Frequency → Controls pitch of the tone

Oscillator → Produces waveform (sine)

Audio Context → Handles playback

All processing happens locally in your browser. No server, no latency excuses.

🎨 Customization
Changing Default Frequency

Modify your JavaScript file:

oscillator.frequency.value = 440; // Default frequency (Hz)
Adding More Controls

You can extend the UI to include:

Volume (GainNode)

Waveform selection (sine, square, sawtooth)

Frequency sliders

⚠️ Safety Warning

High frequencies can damage hearing

Loud output can damage speakers

Avoid prolonged exposure to extreme tones

You only get one pair of ears. Try not to speedrun losing them.

🔮 Future Enhancements

🌊 White / Pink / Brown noise modes
📈 Frequency sweep (auto increase/decrease)
🎚️ Volume control (gain adjustment)
🎛️ Multiple waveform support
💾 Save presets

📄 License

MIT License — free to use, modify, and break.

🧊 Final Note

This project does one thing very well:

Turns numbers into sound.

If that doesn’t impress you, you probably haven’t tried 20Hz at max volume yet.
