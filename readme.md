# OBS Pomodoro Timer Overlay

A lightweight, fully transparent Pomodoro timer overlay designed for OBS Studio.  
Ideal for streamers or anyone who wants a clean, customizable Pomodoro timer displayed on their stream or desktop.

---

## Features

- Transparent background for seamless OBS overlay integration  
- 60-minute work sessions with 10-minute breaks (configurable in code)  
- Session tracking (up to 8 study sessions per day)  
- Pause/resume controls  
- Next/previous session buttons  
- Audible beep at session transitions  
- Session logs saved in browser localStorage  
- Responsive design for various screen sizes  
- Auto-pauses when tab/window loses focus (optional)

---

## Usage

1. Clone or download this repository.
2. Open `obs-pomodoro.html` in a modern browser (Chrome, Edge, Firefox).  
3. Add the HTML file as a Browser Source in OBS with these settings:
   - Width/Height as needed (e.g., 800x200)  
   - Check "Transparent" background (make sure browser source supports it)  
   - Disable interaction for viewers if you want

4. Place `beep.mp3` in the same folder or update the audio source path inside the HTML.

---

## Customization

- **Work and Break Duration**: Edit `workTime` and `breakTime` constants (in seconds) in the script.  
- **Max Sessions**: Change `maxSessions` to adjust how many sessions are counted per day.  
- **Style**: Modify CSS in the `<style>` section for colors, fonts, sizes, shadows, etc.

---

## File Structure




------

---

## Browser Compatibility

Tested on latest versions of:
- Google Chrome  
- Microsoft Edge  
- Mozilla Firefox

---

## License

This project is released under the MIT License. See [LICENSE](LICENSE) for details.

---

## Contributions

Contributions, issues, and feature requests are welcome!  
Feel free to fork the repo and submit a pull request.

---

## Contact

Created by [Your Name or Handle]  
[Optional: Your Email or Website]

---

Enjoy your productive sessions! 🍅
