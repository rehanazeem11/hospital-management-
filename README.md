# Grano - Coffee Affairs — Google Review Assistant

> **"Share your Grano experience. Turn your coffee moment into your own words."**  
> A dedicated, mobile-first Google Review writing assistant custom-built for **Grano - Coffee Affairs, Jubilee Hills, Hyderabad**. Designed for customers scanning tabletop QR codes or counter NFC cards.

---

## Customer Flow (One Simple Page)

```
[QR Code / NFC Card Scanned by Customer]
                     │
                     ▼
  [Grano - Coffee Affairs Branded Assistant Opens]
  • Name & Location: Grano - Coffee Affairs • Jubilee Hills, Hyderabad
  • Select Highlights: Specialty Coffee, Cranberry Brews, Garden Courtyard, Pet-Friendly
  • Optional: Notes on items ordered or experience
  • Choose Tone & Language (English, Hindi, Hinglish)
                     │
                     ▼
       [Click "Generate My Review"]
  • AI crafts unique, grounded, natural review
  • Zero hallucination of unmentioned dishes/orders
                     │
                     ▼
        [Edit, Polish & Copy Draft]
  • Live word & character counters
  • Single-click copy or regenerate
                     │
                     ▼
  [Click "Continue to Google Reviews"]
  • Copies draft to clipboard automatically
  • Opens Grano's official Google review page
  • Customer pastes & submits their review on Google
```

---

## Key Features

1. **Direct Grano Integration**:
   - Pre-configured for **Grano - Coffee Affairs, Jubilee Hills, Hyderabad**.
   - No searching, no manual venue selection, and no login required for customers.
2. **Minimal & Fast UI/UX**:
   - Clean cafe aesthetic: white background, dark typography, subtle green accents.
   - Mobile-first, lightweight, and ultra-fast.
3. **Genuine & Varied AI Generation**:
   - Supports **English**, **Hindi (हिंदी)**, and modern **Hinglish**.
   - Anti-repetition engine guarantees each customer gets a newly composed draft.
   - Option to generate **3 alternatives** simultaneously.
4. **Google Reviews Deep-Link**:
   - Opens Grano's official Google review modal.
   - Verified listing: `https://www.google.com/maps/place/Grano+-+Coffee+Affairs/@17.427384,78.41366,17z/...`
   - Direct review pop-up: `https://www.google.com/search?q=grano+coffee+affairs+reviews#lrd=0x3bcb91866f263499:0xb472ea500896e982,3,,,,`
   - Guidance notice: *"Review your text, copy it, and paste it into Google Reviews. Submit your review on Google."*
5. **Admin Settings**:
   - Configurable Google review URL.
   - Live link test button.
   - Provider settings (Gemini API, OpenAI, or the built-in natural engine).
6. **Review History**:
   - Preserves generated drafts locally with search, copy, and delete controls.

---

## Getting Started

### 1. Installation
```bash
npm install
```

### 2. Configuration (`.env` or Admin Settings)
```env
PORT=3000
GOOGLE_REVIEW_URL=https://www.google.com/search?q=grano+coffee+affairs+reviews#lrd=0x3bcb91866f263499:0xb472ea500896e982,3,,,,
GEMINI_API_KEY=
OPENAI_API_KEY=
```

> **Note**: An external API key is **optional**. The app comes with an integrated **Grano Natural Engine** that works immediately without configuring an API key.

### 3. Run Locally
```bash
npm start
```
Open **[http://localhost:3000](http://localhost:3000)** in your browser.
