# DeckMetrics — MTG Deck Ledger 🃏

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

**DeckMetrics** (formerly Vault) is a lightweight web application for building and managing Magic: The Gathering decks. This project serves as a personal, private deck ledger that integrates directly with the Scryfall API to fetch real-time card data, high-quality images, and current market prices.

---

## ✨ Key Features

* **Local-First Deck Management:** Create, rename, and delete multiple decks seamlessly. All data is saved instantly and securely in your browser using `localStorage`.
* **Integrated Card Search:** Search for cards directly by name (e.g., *Sol Ring* or *Lightning Bolt*) using the extensive Scryfall database.
* **Real-Time Price Tracking:** Automatically calculates and displays the total deck value in USD. Includes a "Refresh prices" button to sync the latest market values for all cards at once.
* **Automated Card Grouping:** Cards added to your deck are automatically sorted by type (*Creatures, Planeswalkers, Instants, Sorceries, Artifacts, Enchantments, Battles,* and *Lands*).
* **Visual Customization:** Set any card's artwork as the representative cover image for your deck.
* **Export & Import (JSON):** Your data isn't locked in. Back up your decks by exporting them as JSON files, or import previously saved JSON files to restore a decklist.
* **Interactive Card Previews:** Click on any card thumbnail to open a detailed preview dialog featuring high-resolution artwork, mana cost, type line, oracle text, Power/Toughness (P/T), and current market price.
* **Network Status Detection:** A real-time network indicator in the top right corner shows whether you are currently "connected" to the API or "offline".

## 💻 Tech Stack

This project is built purely on the client-side (frontend) with zero dependencies or heavy frameworks:
* **HTML5 & CSS3:** Semantic structure and responsive layout using native CSS Grid, Flexbox, and custom CSS variables for a premium dark-mode aesthetic.
* **Vanilla JavaScript (ES6+):** Handles application logic, DOM manipulation, state management, and local storage.
* **Scryfall API:** An open REST API utilized asynchronously via `fetch` to retrieve card metadata and imagery.

## 🚀 Getting Started Locally

Because this project is 100% client-side, the setup process is incredibly simple and requires no backend servers (like Node.js).

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yaekali/DeckMetrics.git
   ```
2. **Open the main file:**
   Simply double-click `commander vault.html` (or whatever you named the main file) to open it in any modern web browser (Chrome, Firefox, Safari, Edge).
3. *(Optional)* Rename the main file to `index.html` if you plan to host this application for free using **GitHub Pages**.

## 🤝 Contributing
If you find a bug or have an idea for a new feature, feel free to open an **Issue** or submit a **Pull Request**.

## 📝 Author
**Muhammad Akbar Firdaus**
* GitHub: [@yaekali](https://github.com/yaekali)

## 📜 License
This project is open-source and available under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

*Disclaimer: Magic: The Gathering, including card images, mana symbols, and oracle text fetched via the Scryfall API, is copyright Wizards of the Coast, LLC. This project is a fan-made tool and is not affiliated with, endorsed, sponsored, or specifically approved by Wizards of the Coast.*