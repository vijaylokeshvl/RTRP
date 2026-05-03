# StyleSense | AI-Powered Fashion Stylist

StyleSense is an advanced AI fashion assistant designed to help you elevate your wardrobe and discover your unique style.

## Features

- **Outfit Analyzer**: Upload photos and get expert AI feedback on your looks.
- **AI Outfit Generator**: Create complete outfits for any occasion or season.
- **Digital Wardrobe**: Manage your clothing items in a centralized digital space.
- **Trend Explorer**: Stay ahead of the curve with AI-curated fashion trends.
- **Style Quiz**: Build a personalized style profile to get better recommendations.

## Tech Stack

- **Frontend**: React 18, TypeScript, Vite
- **Styling**: Tailwind CSS, shadcn/ui, Framer Motion
- **Backend**: Supabase (Auth, Database, Storage, Edge Functions)
- **AI**: Google Gemini & other advanced models

## Getting Started

### Prerequisites

- Node.js & npm

### Installation

1. Clone the repository
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the development server:
   ```sh
   npm run dev
   ```

## Environment Variables

Ensure you have the following environment variables configured in your Supabase project:

- `AI_GATEWAY_KEY`: Your API key for AI services.
- `SUPABASE_URL`: Your Supabase project URL.
- `SUPABASE_ANON_KEY`: Your Supabase anonymous key.
