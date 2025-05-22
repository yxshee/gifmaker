

<!-- Badges -->
<p align="center">
  <img src="https://img.shields.io/badge/AI-Gemini_2.0-blueviolet?style=flat-square" alt="Gemini AI"/>
  <img src="https://img.shields.io/badge/Built_with-TypeScript-3178c6?style=flat-square" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/License-CC0_1.0-lightgrey?style=flat-square" alt="License"/>
</p>



<h1 align="center"> GIF Maker</h1>
<p align="center"><b>Turn your text prompts into charming animated doodles with Gemini AI!</b></p>

<div align="center">
  <img src="https://github.com/user-attachments/assets/89b18abd-98d3-4514-a2c6-3df601986907" alt="Demo GIF" width="40%" style="border-radius:12px;margin:20px 0"/>
</div>



---

## ✨ Features

<div align="center">

| 🧙‍♂️ | **AI-Powered Doodles** | Generate animated doodle GIFs from text using Gemini 2.0 |
|----|----------------------|----------------------------------------------------------|
| 🖼️ | **Frame-by-Frame**    | Watch the animation build with real-time frame generation |
| 🔄 | **Smooth Animation**  | Automatically creates smooth GIFs from generated frames   |
| 💾 | **Easy Download**     | Save your magical creations with one click                |
| 🎨 | **Beautiful UI**      | Clean, responsive interface with light/dark mode support  |

</div>

---


## 🌀 How it Works

```mermaid
flowchart LR
    A[Type your prompt] --> B[Gemini generates frames]
    B --> C[View individual frames]
    C --> D[Frames combined into GIF]
    D --> E[Download your creation]
```

</div>

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher)
- A [Gemini API Key](https://ai.google.dev/)

### Installation

```bash
git clone https://github.com/your-username/gifmaker.git
cd gifmaker
npm install
```

### Configuration

Create a `.env.local` file in the root directory and add your Gemini API key:

```env
GEMINI_API_KEY=your-gemini-api-key-here
```

### Run Locally

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to start creating GIFs!

---

## 🗂️ Actual Project Structure

```plaintext
gifmaker/
├── src/             # Source files
│   ├── index.tsx    # Main application code
│   └── index.css    # Styles
├── index.html       # HTML entry point
├── .env.local       # Environment variables for API key
├── vite.config.ts   # Vite configuration
├── tsconfig.json    # TypeScript configuration
├── package.json     # Dependencies and scripts
└── ...
```

---

## 🛠️ How to Use

<div align="center">
  <table>
    <tr>
      <td width="33%">
        <img src="https://via.placeholder.com/300/8a2be2/ffffff?text=1.+Enter+Prompt" style="border-radius:8px"/>
        <p align="center">Enter your creative prompt</p>
      </td>
      <td width="33%">
        <img src="https://via.placeholder.com/300/8a2be2/ffffff?text=2.+Generate" style="border-radius:8px"/>
        <p align="center">Click "Generate Magic"</p>
      </td>
      <td width="33%">
        <img src="https://via.placeholder.com/300/8a2be2/ffffff?text=3.+Download" style="border-radius:8px"/>
        <p align="center">Download your GIF!</p>
      </td>
    </tr>
  </table>
</div>

### Example Prompts to Try

- "a cat playing with yarn"
- "a rocket launching into space"
- "a dolphin jumping through waves"
- "a dancing robot"

---

## 🧠 Tech Under the Hood

- **Gemini AI**: Powers the image generation with the `gemini-2.0-flash-preview-image-generation` model
- **gifenc**: Processes and combines frames into smooth GIFs
- **Vite**: Fast, modern frontend tooling

---

## 📄 License

CC0 1.0 Universal. See [LICENSE](LICENSE) for details.

---

## 🙋‍♂️ Support & Contribution

Got an idea or found a bug? Feel free to:
- Open an issue
- Submit a pull request
- Star the repository!

---

<p align="center">
  <img src="https://readme-arts.vercel.app/api/shapes?type=spacer&height=40&width=600&fill=transparent" alt="spacer"/>
  <br/>
  <b>Made with ✨ AI magic and human creativity</b>
</p>
