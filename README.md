# Wikipedia Chatbot

*A chatbot for talking about Wikipedia articles.*

## How to use it

1. **Clone the repo**
```bash
git clone https://github.com/nating/wikipedia-chatbot.git
```
2. **Install dependencies**:
```bash
npm install
```
3. Add your OpenAI APK key .env.local in the project root. For example:
```bash
OPENAI_API_KEY=<your OpenAI API key>
CHUNK_SIZE=4000
EMBEDDING_MODEL=text-embedding-3-small
MODEL=gpt-4o-mini
```
4. Run the app locally:
```bash
npm run dev
```
5. Open your browser at http://localhost:3000 to use the chatbot.
6. Paste in a Wikipedia URL, press `Scrape`, and wait for the scraping/embedding to complete.
7. Ask any questions you want about your Wikipedia page!

Feel free to modify .env.local to mess around with the chunking / models!
