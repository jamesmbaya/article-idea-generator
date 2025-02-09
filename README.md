[![Open in GitPod](https://img.shields.io/badge/Gitpod-Ready--to--Code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/Olanetsoft/article-idea-generator) [![GitHub issues](https://img.shields.io/github/issues/Olanetsoft/article-idea-generator)](https://github.com/Olanetsoft/article-idea-generator/issues)
[![GitHub forks](https://img.shields.io/github/forks/Olanetsoft/article-idea-generator)](https://img.shields.io/github/forks/Olanetsoft/article-idea-generator)
[![GitHub stars](https://img.shields.io/github/stars/Olanetsoft/article-idea-generator)](https://img.shields.io/github/stars/Olanetsoft/article-idea-generator)
[![GitHub watchers](https://img.shields.io/github/watchers/Olanetsoft/article-idea-generator?style=label=Watch)](https://github.com/Olanetsoft/article-idea-generator)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![GitHub repo size](https://img.shields.io/github/repo-size/Olanetsoft/article-idea-generator)](https://github.com/Olanetsoft/article-idea-generator)

## [Article Idea Generator](https://www.articleideagenerator.com/)

This simple tool generates article ideas for your blog or website. It's a great way to get started with your content marketing strategy.

[![Article Idea Generator](./public/screenshot.png)](https://www.articleideagenerator.com/)
[![Article Idea Generator](./public/screenshot-2.png)](https://www.articleideagenerator.com/)

## How to use

1. Go to [https://www.articleideagenerator.com/](https://www.articleideagenerator.com/)
2. Enter any related keyword to the topic you have in mind and click `Enter.`
`Optional`: click on the `Enable SEO and CLickbait feature` to get some ideas that would easily rank on search engines
3. Four different article ideas will be generated; copy any of the generated article idea
4. Paste it into your favourite content editor
5. Write your article
6. Publish it


## How it works

The [OpenAI GPT-3 API](https://openai.com/api/) (text-davinci-003) and [Vercel Edge streaming](https://vercel.com/features/edge-functions) features are used in this application. Based on the user's input, it creates a prompt, sends it to the GPT-3 API using a Vercel Edge function, and streams the response back to the application.

## Running Project Locally

1. Fork the repo
2. Clone the repo
3. After cloning the repo, go to [OpenAI](https://beta.openai.com/account/api-keys) to make an account and generate your API key
4. Rename the `.env.example` file on the root of the project to `.env`, then paste your API key in the `.env` file
5. Run `npm install` to install all the dependencies
6. Run `npm run dev` to start the project
7. Go to [http://localhost:3000](http://localhost:3000) to see the project running

## Contributing

If you want to contribute to this project, please read the [contributing guide](./CONTRIBUTING.md). If you have any ideas or suggestions, feel free to open an issue or a pull request. 

If you like this project, please give it a star ⭐️


## Contributors 💪

Thanks for spending your time helping `Article Idea Generator` grow. Happy Hacking 🍻

[![Contributors](https://contrib.rocks/image?repo=Olanetsoft/article-idea-generator)](https://github.com/Olanetsoft/article-idea-generator/edit/main/README.md)

## Stargazers ⭐️

[![Stargazers](https://git-lister.onrender.com/api/stars/Olanetsoft/article-idea-generator?limit=15)](https://github.com/Olanetsoft/article-idea-generator)


## Acknowledgement

Built with 💗 by [Olanetsoft](https://twitter.com/olanetsoft) & [Kelvin](https://twitter.com/iam_kelvinjnr). Inspired by [Nutlope](https://twitter.com/nutlope), powered by [Open AI](https://openai.com/) & [Vercel Edge Functions](https://vercel.com).
