The AI Multi-Modal Analyzer is a single-page web application that demonstrates the capabilities of modern large language models (LLMs) in targeted visual analysis. It classifies uploaded or captured images into categories—Network Diagram, Fruit, or General—and executes specialized analysis pipelines for each.
2. Technical Stack & Environment
Component	Technology / Role
Frontend	HTML5, Tailwind CSS - Ensures a modern, fully responsive design
Logic & State	React (via CDN), Babel - Manages UI, state, and asynchronous operations
AI Integration	Gemini API (gemini-2.5-flash-preview-09-2025) - Handles image classification, architectural analysis, and code generation
Camera Access	Native JavaScript (getUserMedia) - Enables live scanning and image capture
