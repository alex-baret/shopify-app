# AI-Powered Bulk Product Description Generator

A Shopify app that helps merchants generate and update product descriptions in bulk using AI.

## Features

- **Bulk Product Selection**: Select products by collection, tag, or individual checkboxes
- **AI-Powered Generation**: Uses OpenAI API to generate compelling product descriptions
- **Style Customization**: Choose from different tones (professional, fun, casual, etc.)
- **Review & Edit**: Preview and modify generated descriptions before publishing
- **One-Click Publish**: Update all selected products instantly
- **Shopify Native**: Seamlessly integrates with your Shopify store

## Tech Stack

- **Frontend**: React with TypeScript
- **Backend**: Node.js with Express
- **Database**: SQLite (for development), PostgreSQL (for production)
- **AI**: OpenAI API
- **Shopify Integration**: Shopify App Bridge, Admin API
- **Styling**: Tailwind CSS

## Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn
- Shopify Partner account
- OpenAI API key

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables:
   ```bash
   cp .env.example .env
   ```
4. Configure your `.env` file with:
   - `SHOPIFY_API_KEY`
   - `SHOPIFY_API_SECRET`
   - `SCOPES`
   - `OPENAI_API_KEY`
   - `HOST`

5. Start the development server:
   ```bash
   npm run dev
   ```

## Development

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run test` - Run tests
- `npm run lint` - Run ESLint

## Deployment

The app is ready for deployment to platforms like:
- Heroku
- Railway
- Vercel
- AWS

## License

MIT
