# 🎤 Karaoke Transcriber

A command-line tool that converts any video file into a karaoke-style subtitled video using OpenAI Whisper and FFmpeg.

---

## 📖 About the Project

**Karaoke Transcriber**:

- Extracts audio from a video file
- Transcribes the speech using Whisper (openai-whisper)
- Generates `.srt` subtitles
- Burns the subtitles back into the video using FFmpeg

This is ideal for:

- Karaoke/lyric video generation
- Captioning interviews, speeches, or educational content
- Language learning and accessibility

---

## ⚙️ Minimum Requirements

Ensure the following tools and libraries are installed on your system:

### System Requirements

- [Node.js](https://nodejs.org/) (v16 or higher)
- [Python 3](https://www.python.org/)
- [FFmpeg](https://ffmpeg.org/)

### Python Dependencies

Install these via pip:

```bash
pip3 install openai-whisper srt
```

You can also verify your environment setup using:

```bash
node check-env.js
```

This script will check for FFmpeg, Python 3, and required Python packages.

---

## 📦 Install via npm (Published Version)

Once the package is published, you can install it globally:

```bash
npm install -g karaoke-transcriber
```

Then use it from anywhere via:

```bash
karaoke-transcriber --input path/to/input.mp4 --output path/to/output.mp4
```

---

## 🧪 Run Locally (Development)

### Step 1: Clone the Repository

```bash
git clone https://github.com/rahulSheregar/karaoke-transcriber.git
cd karaoke-transcriber
```

### Step 2: Install Node.js dependencies

```bash
npm install
```

### Step 3: Build the TypeScript files

```bash
npm run build
```

### Step 4: Run the CLI

```bash
node dist/index.js --input path/to/video.mp4 --output path/to/output.mp4
```

---

## 🗂 Project Structure

```
karaoke-transcriber/
│
├── dist/                 # Compiled JavaScript output
├── node_modules/         # npm dependencies
├── python_backend/
│   └── karaoke_gen.py    # Python script for processing audio/video
├── src/
│   └── index.ts          # TypeScript CLI entry point
│
├── check-env.js          # System dependency checker (optional)
├── package.json
├── tsconfig.json
├── README.md
```

---

## 👤 Author

Created by **Rahul Sheregar**

- GitHub: [@rahulSheregar](https://github.com/rahulSheregar)

---

## 📄 License

MIT License

```

```
