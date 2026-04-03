# KBeauty — Korean Cosmetics Web Shop

> UX Design & Research Project | Human-Computer Interaction

A complete UX design project for a Korean cosmetics web shop with integrated ingredient analysis. The application allows users to browse products filtered by skin type, analyze ingredient safety, take a skin type quiz, and manage orders — all in one place.

---

## The Problem

Users interested in Korean skincare currently have to visit multiple platforms to research products: web shops, YouTube reviews, Instagram, and separate ingredient checker tools like INCIDecoder or SkinCarisma. No existing solution combines **shopping + ingredient analysis + personalized recommendations** in one place.

---

## The Solution

KBeauty is a web shop that puts ingredient transparency at the center of the shopping experience. Every product includes a full INCI list with safety ratings for each ingredient, and a built-in analyzer lets users paste any ingredient list and instantly see what's safe, comedogenic, or potentially irritating for their skin type.

---

## Features

| Feature | Description |
|---|---|
| Product browsing | Filter by category and skin type |
| Ingredient analyzer | Paste any INCI list and get a full safety breakdown |
| Skin type quiz | 6-question quiz with personalized product recommendations |
| Shopping cart | Promo codes, free shipping threshold, quantity management |
| Order tracking | View current and past orders with status updates |
| Wishlist | Save products for later |
| Restock & sale alerts | Get notified when a previously purchased product goes on sale or back in stock |

---

## UX Process & Deliverables

### 1. Product-Market Fit Matrix
Analysis of the problem space, user needs, existing solutions, and success metrics. Includes interviews with two real potential users.

**User research highlights:**
- User 1 (49, teacher): sensitive skin with sun allergy — needs automatic detection of photosensitive ingredients
- User 2 (21, law student): acne-prone skin — needs instant comedogenic ingredient flagging and a modern minimalist design

📄 [`docs/PMF_FINAL_KBeauty.pdf`](docs/PMF_FINAL_KBeauty.pdf)

---

### 2. HTA Diagram (Hierarchical Task Analysis)
Full task breakdown of all 6 main user goals, including required information, operation sequences, possible outcomes, and error handling for each task.

**Main tasks analyzed:**
- Product browsing & filtering
- Ingredient analysis
- Purchase flow
- Skin type test
- Order tracking
- Managing purchased products & notifications

📄 [`docs/HTA_dijagram_KBeauty.pdf`](docs/HTA_dijagram_KBeauty.pdf)
📄 [`docs/HTA_dijagram_KBeauty_tekstualni_opis.pdf`](docs/HTA_dijagram_KBeauty_tekstualni_opis.pdf)

---

### 3. Use Case Diagram
UML use case diagram covering both guest and registered user flows, including checkout, wishlist, profile editing, and notification management.

📄 [`docs/Use_case_dijagram_KBeauty.pdf`](docs/Use_case_dijagram_KBeauty.pdf)

---

### 4. UI Prototype (Figma)
High-fidelity prototype covering all key screens with UI pattern documentation for each screen.

**Screens included:**
- Home page
- Product listing with search & filters
- Product detail with ingredient analysis
- Shopping cart with promo code
- Ingredient analyzer tool
- Skin type quiz (6 steps + results)

**UI patterns used:** Navigation bar, Card layout, Wizard pattern, Progressive disclosure, Real-time feedback, Primary/Secondary actions, Error prevention

📄 [`docs/Prototip_KBeauty.pdf`](docs/Prototip_KBeauty.pdf)  
🖼️ [`prototype/`](prototype/) — Individual screen exports

> 🚧 Full implementation coming soon via Figma Make.

---

## Tech Stack (Planned)

| Layer | Technology |
|---|---|
| Frontend | Figma Make (React export) |
| Styling | Tailwind CSS |
| Backend | TBD |

---

## Author

**Asja Brčaninović** — IB230030  
Software Engineering, Faculty of Information Technologies  
University "Džemal Bijedić", Mostar  
Course: Human-Computer Interaction | 2025/2026
