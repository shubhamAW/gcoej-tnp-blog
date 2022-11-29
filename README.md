This is a [Next.js](https://nextjs.org/) blog using [Notions Public API](https://developers.notion.com).

__Demo:__ [https://notion-blog-nextjs-coral.vercel.app](https://tnp-gcoej.vercel.app/)



## Getting Started

First, follow Notions [getting started guide](https://developers.notion.com/docs/getting-started) to get a `NOTION_TOKEN` and a `NOTION_DATABASE_ID`, then add them to a file called `.env.local`.

As a reference here's the Notion table I am using: https://shubhamaw.notion.site/dacc47832c074652b58f2ea8d8fa00e4?v=6c527ce04d52416ebc2e8a202b749e89

```
NOTION_TOKEN=
NOTION_DATABASE_ID=
```

Install dependencies

```bash
npm install
# or
yarn
```

Start the server with

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

#### Deploy to vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/)
