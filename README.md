# Vue-Nuxt
Docker-composeでVue/Nuxt.jsを環境構築

## 手順
1, 「Dockerfile」と「docker-compose.yml」を作成・記述<br>
2, ターミナルで「$ docker-compose build」<br>
3, 続いて「$ docker-compose run --rm nuxt npx create-nuxt-app」　
4, 下記の「設定」をやる<br>
5, 「docker-compose up -d」<br>
6, 「localhost:3000」にアクセス

## 設定
? Project name: 任意<br>

? Programming language: TypeScript<br>

? Package manager: Yarn<br>

? UI framework: Vuetify.js <br>

? Nuxt.js modules: Axios - Promise based HTTP client, Progressive Web App (PWA) <br>

? Linting tools: ESLint, Prettier <br>

? Testing framework: Jest <br>

? Rendering mode: Universal(SSR/SSG) <br>

?Deployment target: Static (Static/JAMStack hosting)<br>

? Development tools: jsconfig.json<br>

? Continuous integration: GitHub Actions (GitHub only)<br>

? What is your GitHub username? : 任意<br>

? Version control system: Git 

## 原因不明
typescriptのディレクトリがGitHubにプッシュできない
