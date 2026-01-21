# Prompt Hub 🌟

**Prompt Hub** is a clean, modern GitHub Pages website to store and share AI prompts.  
Each prompt is displayed in a card with a **Copy Prompt** button, so you can easily copy it for use in AI tools.  

## Features
- Modern, responsive UI with cards and hover effects  
- Fully dynamic — just add your prompts in the code, and new cards are generated automatically  
- Copy-to-clipboard functionality for each prompt  
- Mobile-friendly and desktop-ready  

## How to Use
1. Open the live website: `https://username.github.io/repository-name`  
2. Browse prompts and click **Copy Prompt** to copy the text  

## How to Add New Prompts
1. Open `index.html` in the repository  
2. Locate the `prompts` array in the `<script>` section:  
```javascript
const prompts = [
  "Your first prompt",
  "Your second prompt"
];

