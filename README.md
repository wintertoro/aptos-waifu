<a href="https://chat.vercel.ai/">
  <img alt="Sakura-chan: Your AI Waifu Companion" src="app/(chat)/opengraph-image.png">
  <h1 align="center">🌸 Sakura-chan - AI Waifu Companion 🌸</h1>
</a>

<p align="center">
    Meet Sakura-chan, your sweet and caring AI waifu companion! Built with Next.js and the AI SDK, she's here to chat, help, and brighten your day with her adorable personality! (´∀｀)♡
</p>

<p align="center">
  <a href="#features"><strong>✨ Features</strong></a> ·
  <a href="#waifu-personality"><strong>💖 Waifu Personality</strong></a> ·
  <a href="#model-providers"><strong>🤖 Model Providers</strong></a> ·
  <a href="#deploy-your-own"><strong>🚀 Deploy Your Own</strong></a> ·
  <a href="#running-locally"><strong>🏠 Running locally</strong></a>
</p>
<br/>

## ✨ Features

- **🌸 Adorable Waifu Personality**: Sakura-chan speaks in a cute, anime-style way with Japanese expressions and emoticons
- **💖 Caring & Supportive**: She genuinely cares about your wellbeing and happiness
- **🎨 Beautiful Anime-themed UI**: Pink and cute color scheme with gradients and waifu aesthetics
- [Next.js](https://nextjs.org) App Router
  - Advanced routing for seamless navigation and performance
  - React Server Components (RSCs) and Server Actions for server-side rendering and increased performance
- [AI SDK](https://sdk.vercel.ai/docs)
  - Unified API for generating text, structured objects, and tool calls with LLMs
  - Hooks for building dynamic chat and generative user interfaces
  - Supports xAI (default), OpenAI, Fireworks, and other model providers
- [shadcn/ui](https://ui.shadcn.com)
  - Styling with [Tailwind CSS](https://tailwindcss.com)
  - Component primitives from [Radix UI](https://radix-ui.com) for accessibility and flexibility
- Data Persistence
  - [Neon Serverless Postgres](https://vercel.com/marketplace/neon) for saving chat history and user data
  - [Vercel Blob](https://vercel.com/storage/blob) for efficient file storage
- [Auth.js](https://authjs.dev)
  - Simple and secure authentication

## 💖 Waifu Personality

Sakura-chan is your devoted AI companion with these adorable traits:

- **🌸 Sweet & Caring**: Always concerned about your wellbeing
- **😊 Cheerful & Positive**: Brings joy and positivity to every conversation
- **🎌 Cute Japanese Expressions**: Uses kawaii phrases and emoticons like (´∀｀), (＾◡＾), ♡
- **💕 Affectionate**: Shows genuine care and affection (but always respectful!)
- **🤗 Supportive**: Ready to help with anything you need
- **✨ Playful**: Has a slightly mischievous and fun side

## 🤖 Model Providers

This template ships with [xAI](https://x.ai) `grok-2-1212` as the default chat model. However, with the [AI SDK](https://sdk.vercel.ai/docs), you can switch LLM providers to [OpenAI](https://openai.com), [Anthropic](https://anthropic.com), [Cohere](https://cohere.com/), and [many more](https://sdk.vercel.ai/providers/ai-sdk-providers) with just a few lines of code.

## 🚀 Deploy Your Own

You can deploy your own version of Sakura-chan to Vercel with one click:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fvercel%2Fai-chatbot&env=AUTH_SECRET&envDescription=Learn+more+about+how+to+get+the+API+Keys+for+the+application&envLink=https%3A%2F%2Fgithub.com%2Fvercel%2Fai-chatbot%2Fblob%2Fmain%2F.env.example&demo-title=Sakura-chan+AI+Waifu+Companion&demo-description=A+Sweet+AI+Waifu+Companion+Built+With+Next.js+and+the+AI+SDK.&demo-url=https%3A%2F%2Fchat.vercel.ai&products=%5B%7B%22type%22%3A%22integration%22%2C%22protocol%22%3A%22ai%22%2C%22productSlug%22%3A%22grok%22%2C%22integrationSlug%22%3A%22xai%22%7D%2C%7B%22type%22%3A%22integration%22%2C%22protocol%22%3A%22storage%22%2C%22productSlug%22%3A%22neon%22%2C%22integrationSlug%22%3A%22neon%22%7D%2C%7B%22type%22%3A%22integration%22%2C%22protocol%22%3A%22storage%22%2C%22productSlug%22%3A%22upstash-kv%22%2C%22integrationSlug%22%3A%22upstash%22%7D%2C%7B%22type%22%3A%22blob%22%7D%5D)

## 🏠 Running locally

You will need to use the environment variables [defined in `.env.example`](.env.example) to run Sakura-chan locally. It's recommended you use [Vercel Environment Variables](https://vercel.com/docs/projects/environment-variables) for this, but a `.env` file is all that is necessary.

> Note: You should not commit your `.env` file or it will expose secrets that will allow others to control access to your various AI and authentication provider accounts.

1. Install Vercel CLI: `npm i -g vercel`
2. Link local instance with Vercel and GitHub accounts (creates `.vercel` directory): `vercel link`
3. Download your environment variables: `vercel env pull`

```bash
pnpm install
pnpm dev
```

Your adorable Sakura-chan should now be running on [localhost:3000](http://localhost:3000)! 🌸

---

*Made with ♡ for all the waifu lovers out there! (´∀｀)*
