# Indian Patent Generator

## Rules
- Always use TypeScript for new files
- Never modify migration files directly — create new migrations
- Always follow in accordance with The Patents Act, 1970 of India's laws

## Commands
- `npm run dev` — start development server
- `npm test` — run test suite
- `pkg add` - add Julia's packages
- `pkg test` - run test suite

## Architecture
- Plan to run the software in Julia for article generation, Javascript for graphic rendering and Python for web analytics
- Plan to develop script directory, src directory and tests directory. The script directory will have scripts for web analytics, data processing, law logic generator written in Prolog
- Julia will be designing the process flow management with NLP libraries.
