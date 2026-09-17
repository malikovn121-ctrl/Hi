# PetHealth Tracker AI

An iOS-style pet health tracker web application featuring AI photo scanner analysis, water intake logging, medication tracking, reminders, and activity progress rings.

## Features

- **Pet Profile & Onboarding**: Custom pet profile setup (Dog, Cat, Rabbit, Bird, etc.) with breed, age, and health goals.
- **AI Scanner**: Pet health photo-check scanner powered by Gemini AI to detect visible signs of irritation, eye/ear conditions, skin/coat issues, and wellness tips.
- **Water Tracker**: Daily hydration log with interactive cup fill animation and target progress.
- **Medication & Reminders**: Scheduled dosages, completion checkboxes, and notifications.
- **Activity & Vitals Ring**: Daily activity monitoring and health metrics.

## Getting Started

### Prerequisites

- Node.js 18+
- npm or bun

### Installation

```bash
npm install
```

### Environment Variables

Copy `.env.example` to `.env` and provide your Gemini API key:

```bash
cp .env.example .env
```

Set:
```
GEMINI_API_KEY=your_gemini_api_key_here
```

### Development

```bash
npm run dev
```

The application runs at `http://localhost:3000`.

### Production Build

```bash
npm run build
npm start
```
