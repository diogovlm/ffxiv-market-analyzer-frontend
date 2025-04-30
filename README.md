# FFXIV Market Intelligence App – Frontend

This is the **frontend** of the FFXIV Market Intelligence App, a tool designed to analyze Final Fantasy XIV marketboard data using the [Universalis API](https://universalis.app/), [Teamcraft API](https://ffxivteamcraft.com) and [XIVAPI](https://xivapi.com/). It consumes the backend services from the [FFXIV Market Intelligence Backend](https://github.com/diogovlm/ffxiv-market-analyzer-backend).

---

## ⚠️ Status: Work in Progress

This project is currently under active development. The frontend is not fully functional yet.

If you're looking to explore what is already implemented, please check out the backend repository linked above.

---

## 📌 MVP1 – Planned Frontend Features

These are the features we plan to implement in the first milestone (MVP1):

### Basic Item Search

- Search input for item ID or name (will use XIVAPI).
- Show item details such as name, icon, and current price in a selected world.

### Arbitrage Tool

- Allow selecting a sell world and multiple buy worlds.
- Display cheapest and most expensive worlds with calculated profit.

### Crafting Profit Analyzer

- Input an item or recipe ID.
- Show list of required ingredients and their prices.
- Display total material cost, selling price, and profit.

### Alert System

- A button to turn the alert system on/off.
- Visual display of generated alerts with profit and market details.
- Frontend trigger to run the scan with custom filters.

---

## 🔧 Technologies

- React + TypeScript
- Axios
- SASS (SCSS)
- Backend Integration via RESTful API

---

## 📦 Installation (Soon)

Once the first implementation is complete, you’ll be able to:

```bash
git clone https://github.com/diogovlm/ffxiv-market-frontend.git
cd ffxiv-market-frontend
npm install
npm run dev
```

## Related Repositories

Backend API (Node.js + MongoDB): https://github.com/diogovlm/ffxiv-market-analyzer-backend

## Contributions

This is a personal portfolio project. Feel free to suggest features or open pull requests.
