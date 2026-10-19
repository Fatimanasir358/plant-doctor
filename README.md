# Plant Doctor

Upload a plant photo and get an AI health assessment with recommendations.

## Run locally
1. `npm install -g netlify-cli`
2. `cp .env.example .env` and add your Anthropic API key
3. `netlify dev` and open http://localhost:8888

## Deploy
1. Push this folder to a GitHub repository.
2. In Netlify: Add new site → Import an existing project → select the repo.
3. Site configuration → Environment variables → add `ANTHROPIC_API_KEY`.
4. Trigger a deploy.

The AI result is based on a photo and is not a substitute for a local expert.
