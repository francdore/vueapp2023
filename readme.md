# vue-app-2023

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin) to make the TypeScript language service aware of `.vue` types.

If the standalone TypeScript plugin doesn't feel fast enough to you, Volar has also implemented a [Take Over Mode](https://github.com/johnsoncodehk/volar/discussions/471#discussioncomment-1361669) that is more performant. You can enable it by the following steps:

1. Disable the built-in TypeScript Extension
    1) Run `Extensions: Show Built-in Extensions` from VSCode's command palette
    2) Find `TypeScript and JavaScript Language Features`, right click and select `Disable (Workspace)`
2. Reload the VSCode window by running `Developer: Reload Window` from the command palette.

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Type-Check, Compile and Minify for Production

```sh
npm run build
```

### Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
npm run test:unit
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```


Project Idea: Movie Recommendation App

Description:
Create a movie recommendation app using Vue 3. Users should be able to search for movies, view movie details, and get personalized recommendations based on their preferences.

Features:

User Registration and Authentication: Allow users to sign up and log in to the app.
Movie Search: Implement a search functionality that allows users to search for movies by title, genre, or any other relevant criteria.
Movie Details: Display detailed information about a selected movie, including title, description, release date, rating, and any other relevant details.
User Ratings and Recommendations: Allow users to rate movies they have watched and use this data to provide personalized movie recommendations to each user.
Responsive Design: Ensure that the app is mobile-friendly and adapts well to different screen sizes.
Additional Challenges (Optional):
To further demonstrate your skills, you can add additional features or challenges to the project:

Implement pagination or infinite scrolling for the movie search results.
Include a feature for users to create and manage their own movie watchlists.
Use a third-party movie API to fetch movie data, such as TMDB API.
Implement real-time updates using WebSockets to show the number of people currently watching a movie.
By building this project, you'll showcase your proficiency in Vue 3, demonstrate your ability to handle data management, user authentication, and deliver a responsive and interactive user experience.

Remember to pay attention to code organization, component reusability, and following best practices for Vue development. Additionally, consider writing unit tests to showcase your understanding of testing Vue components.
