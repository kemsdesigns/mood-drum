# 🎵 Mood Drum

A cute, responsive drum sequencer with dark/light mode toggle. Make beats with an interactive step sequencer!

## Features

✨ **Design**
- Cute Fredoka font for the display
- Responsive design that works on mobile, tablet, and desktop
- Dark mode / Light mode toggle with persistent theme storage
- No gradients – clean, solid colors

🎮 **Sequencer**
- 16-step sequencer with 6 drum tracks (Kick, Snare, Hi-Hat, Clap, Tom, Perc)
- Interactive grid – tap to toggle steps
- Real-time playback with BPM control (60-200)
- Random pattern generation
- Clear button to reset

📱 **Mobile Optimized**
- Better spacing on mobile devices
- Touch-friendly controls
- Scales beautifully to all screen sizes

## Usage

1. Open `mood-drum.html` in a web browser
2. Tap the grid to enable drum sounds on different steps
3. Adjust BPM with +/- buttons
4. Click PLAY to start the sequencer
5. Use RANDOM to generate patterns or CLEAR to reset
6. Toggle between dark/light mode with the button in the top-right

## Keyboard Shortcut

- **Spacebar** – Play/Stop

## Local Development

```bash
python3 -m http.server 8000
```

Then visit: `http://localhost:8000/mood-drum.html`

## Built With

- HTML5
- CSS3 (with CSS Variables for theming)
- Web Audio API
- Vanilla JavaScript

## License

MIT
