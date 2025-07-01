# Seous AI Platform

A comprehensive AI-powered platform built with Next.js that provides multiple creative generation capabilities including conversation, image generation, video creation, music composition, and code generation.

![Seous AI Dashboard](./public/Screenshot%202025-07-01%20182414.png)

## 🚀 Features

### 🗣️ Conversation

- Advanced conversational AI model
- Natural language processing capabilities
- Interactive chat interface

![Conversation Interface](./screenshots/conversation.png)

### 🎨 Image Generation

- Text-to-image generation
- Customizable output formats (512x512, etc.)
- Multiple image generation options
- Example: "A picture of a horse in Swiss alps"

![Image Generation](./screenshots/image-generation.png)

### 🎬 Video Generation

- Transform text prompts into videos
- Creative scene generation
- Example: "Campfire at night in a snowy forest with starry sky in the background"

![Video Generation](./screenshots/video-generation.png)

### 🎵 Music Generation

- AI-powered music composition
- Various musical styles and instruments
- Example: Piano solo generation

![Music Generation](./screenshots/music-generation.png)

### 💻 Code Generation

- Generate code from descriptive text
- Support for multiple programming languages
- React hooks and component generation
- Example: "Simple toggle button using react hooks"

![Code Generation](./screenshots/code-generation.png)

## 🛠️ Tech Stack

- **Framework**: Next.js
- **Frontend**: React with TypeScript
- **Styling**: Tailwind CSS (based on UI design)
- **UI Components**: Custom component library
- **Icons**: Lucide React (inferred from design)

## 📁 Project Structure

```
seous-ai/
├── components/
│   ├── ui/
│   ├── layout/
│   │   ├── Sidebar.tsx
│   │   └── Dashboard.tsx
│   ├── conversation/
│   ├── image-generation/
│   ├── video-generation/
│   ├── music-generation/
│   └── code-generation/
├── pages/
│   ├── dashboard/
│   ├── conversation/
│   ├── image-generation/
│   ├── video-generation/
│   ├── music-generation/
│   ├── code-generation/
│   └── settings/
├── lib/
│   ├── ai/
│   └── utils/
├── public/
│   └── screenshots/
└── styles/
```

## 🎯 Key Features

### Dashboard

- Clean, modern interface
- Sidebar navigation with organized sections
- Progress tracking (0/7 Free Generations)
- Upgrade options for premium features

### Generation Capabilities

- **Text-to-Image**: High-quality image generation from text prompts
- **Text-to-Video**: Video creation with customizable scenes
- **Text-to-Music**: AI-composed music in various styles
- **Text-to-Code**: Code generation with proper syntax and structure
- **Conversation**: Advanced AI chat capabilities

### User Experience

- Intuitive navigation
- Real-time generation feedback
- Clean, professional design
- Mobile-responsive interface

## 🚦 Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn
- API keys for AI services

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/seous-ai.git
cd seous-ai
```

2. Install dependencies:

```bash
npm install
# or
yarn install
```

3. Set up environment variables:

```bash
cp .env.example .env.local
```

Add your API keys:

```env
NEXT_PUBLIC_APP_URL=http://localhost:3000
OPENAI_API_KEY=your_openai_key
STABILITY_API_KEY=your_stability_key
# Add other AI service keys as needed
```

4. Run the development server:

```bash
npm run dev
# or
yarn dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 🎨 Design System

### Colors

- Primary: Purple gradient (#6366f1 to #8b5cf6)
- Background: Dark navy (#1e293b)
- Sidebar: Darker navy (#0f172a)
- Text: White/Gray scale
- Accent: Orange for illustrations

### Typography

- Clean, modern sans-serif font
- Hierarchical text sizing
- High contrast for readability

### Components

- Rounded corners and smooth transitions
- Consistent spacing and padding
- Modern card-based layouts
- Intuitive iconography

## 📱 Responsive Design

The platform is designed to work seamlessly across:

- Desktop computers
- Tablets
- Mobile devices

## 🔧 Configuration

### AI Service Integration

The platform integrates with multiple AI services:

- OpenAI GPT for conversations and code
- Stability AI for image generation
- Custom models for video and music generation

### Customization

- Theme colors can be modified in `tailwind.config.js`
- Component styling in individual component files
- Layout configurations in layout components

## 🚀 Deployment

### Vercel (Recommended)

```bash
npm run build
vercel deploy
```

### Other Platforms

- Docker deployment ready
- Compatible with Netlify, Railway, and other platforms

## 📊 Features Overview

| Feature             | Status | Description                             |
| ------------------- | ------ | --------------------------------------- |
| 🗣️ Conversation     | ✅     | Advanced AI chat interface              |
| 🎨 Image Generation | ✅     | Text-to-image with customization        |
| 🎬 Video Generation | ✅     | Text-to-video creation                  |
| 🎵 Music Generation | ✅     | AI music composition                    |
| 💻 Code Generation  | ✅     | Code from natural language              |
| ⚙️ Settings         | ✅     | User preferences and account management |
| 🔄 Free/Paid Plans  | ✅     | Tiered usage system                     |

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- OpenAI for GPT models
- Stability AI for image generation
- Vercel for hosting platform
- The open-source community

## 📞 Support

For support, email support@seous-ai.com or join our Discord community.

---

Built with ❤️ using Next.js and modern web technologies.
