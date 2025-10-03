Sky2Soil: From Satellites to Sustainable Farming 🌱🛰️
  
Sky2Soil is an interactive web app bridging satellite tech with sustainable agriculture. Powered by NASA's Earth data (SMAP, MODIS, climate), it helps users explore precision farming through simulations, stories, and tools. Mobile-responsive with a green, intuitive UI.
See the full docs PDF for details.

🚀 Features

Home: Quick cards to modes.
Story Mode: narrative of Hasan's farm transformation .
Sandbox: Virtual 8x6 farm grid; plant/water/harvest with simulated NASA data (moisture, NDVI, etc.); track budget/yield.
AI Advisor: Chatbot for NASA-based tips .
Data Explorer: Browse datasets (soil, veg, climate, crops) with viz placeholders.
Learning Hub: 6 cards on remote sensing & sustainability.
Responsive: Optimized for mobile; animations & sticky nav.

🛠️ Tech

HTML5/CSS3/JS (vanilla, responsive Grid/Flexbox).
Integrations: itch.io embed, HF API/Space, simulated NASA data (AppEEARS-ready).
Fonts: Roboto; no build tools—static site.


🚀 Quick Start
link of this webapp: https://arefin-nibir.github.io/Nasa-apps/
chatbot project link: https://huggingface.co/spaces/psy-mnh14/sky2soil-farmbot-api
Clone: git clone https://github.com/arefin-nibir/sky2soil.git && cd sky2soil
Open index.html in browser (or python -m http.server).
Deploy: GitHub Pages/Netlify.

Note: Internet for AI/itch.io; offline for Sandbox/Learning.
🔧 Development

Scripts: switchMode() (nav), initFarm() (sandbox), sendMessage() (chat).
Extend: Add Chart.js viz, live APIs, lesson modals.
API: POST {question: "..."} to HF endpoint.

🤝 Contributing
Fork → Branch → Commit → PR. Focus on sustainability; add tests/docs.
📄 License
MIT—see LICENSE.
🙏 Acknowledgments
NASA (SMAP/MODIS/GPM), itch.io, Hugging Face. Built by Shams Ul Arefin Nibir, MD Nafis Hussain.

One satellite at a time. 🌍🌾
Updated: October 03, 2025
