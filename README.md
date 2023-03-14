# OpenAI GPT-3.5 (ChatGPT API) Chat App with Streaming Responses

This is a simple chat application built using the ChatGPT API, GPT-3.5. It uses [Next.js](https://nextjs.org/), and builds off of the OpenAI API [quickstart tutorial](https://beta.openai.com/docs/quickstart). Edit the prompt in the generate.ts file to describe the kind of chat character you'd like.

For more on streaming with GPT-3, check out the [vercel edge function tutorial](https://vercel.com/blog/gpt-3-app-next-js-vercel-edge-functions). This has updated the code from the tutorial with the gpt-3.5-turbo model.

You can test out the promps in [ChatGPT](https://chat.openai.com/) and also in the [Playground Chat example](https://platform.openai.com/playground/p/default-chat?mode=chat).

## Setup

Install

```bash
$ npm install
```

Make a copy of the example environment variables file

```bash
$ cp .env.example .env
```

Add your [API key](https://beta.openai.com/account/api-keys) to the newly created `.env` file, and add your prompt as well.

Run the app

```bash
$ npm run dev
```
