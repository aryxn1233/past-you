# Past you

Past you is a modern React application built with Vite and TypeScript. It appears to be an interactive photo album or memory-sharing app, featuring polaroid-style cards, draggable UI elements, and integration with Google's Gemini AI service for enhanced functionality, such as generating captions or processing images.

## Features
- **Polaroid Cards**: Display photos or memories in a nostalgic polaroid format.
- **Draggable UI**: Interactive components using Framer Motion for smooth animations and drag interactions.
- **AI Integration**: Leverages Google Gemini AI via the `geminiService` for potential image analysis or content generation.
- **Responsive Design**: Built with Tailwind CSS for styling, ensuring a clean and mobile-friendly interface.
- **Album Utilities**: Custom utilities in `lib/albumUtils.ts` for managing photo albums or data.

## Tech Stack
- **Frontend**: React 19 with TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS (via `clsx` and `tailwind-merge`)
- **Animations**: Framer Motion
- **AI Service**: Google Generative AI (`@google/genai`)
- **Utilities**: Custom TypeScript libraries

## Prerequisites
- Node.js (v18 or higher)
- npm or yarn

## Installation
1. Clone the repository:
   ```
   git clone <repository-url>
   cd past-forward
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Set up environment variables (if needed):
   - Create a `.env` file in the root directory.
   - Add your Google Gemini API key: `GEMINI_API_KEY=your-api-key-here`
    
## Running the Application
1. Start the development server:
   ```
   npm run dev
   ```

2. Open your browser and navigate to `http://localhost:5173` (or the port shown in the terminal).

3. For production build:
   ```
   npm run build
   ```

4. Preview the build:
   ```
   npm run preview
   ```

## Project Structure
```
past-you/
├── components/
│   ├── Footer.tsx
│   ├── PolaroidCard.tsx
│   └── ui/
│       └── draggable-card.tsx
├── lib/
│   ├── albumUtils.ts
│   └── utils.ts
├── services/
│   └── geminiService.ts
├── App.tsx
├── index.css
├── index.html
├── index.tsx
├── metadata.json
├── package.json
├── tsconfig.json
├── vite.config.ts
└── README.md
```

## Contributing
1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature`
5. Submit a pull request.


