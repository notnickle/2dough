# Noiva-codes & notnickle Collab Project

## TO-DO List Application

##### Project Plan:
    
1. Front-End Languages:
    1. **Javascript** - Framework being Vue.JS
    2. **CSS**
    3. **HTML**

2. Back-End Languages:
    1. **Python**

3. Methodology: **Pair Programming**
    1. We want to be able to learn from this project and get experience in the
    full-stack experience of building an application
4. Server Hosting: Undecided on which host to use, needs more research. Looking for a
    free solution
5. MVP - Minimal Viable Product
    1.  Create Row View of Tasks ![Row View of Tasks](https://images.prismic.io/smarttask/d1c1083c-db73-4562-917f-976f739d15ca_SmartTask-List-view.jpg?auto=compress,format "This is an example image.")
    2.  Buckets of Priorities as seen in the image above.
    3.  Able to open singular tasks after clicking on the task name. (Read Tasks)
    4.  Create Tasks
    5.  Delete Tasks
    6.  Update Tasks
    7.  Storing task information... If I leave the website, it should save my information
    when I come back

# 2dough_list

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