# To-do using React and Typescript

![Screenshot](https://imgur.com/lDZoyUs.png)

<p align="center">  
  <a href="#about">About</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#requirements">Requirements</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#how-to-run">How to run</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#made-using">Techs used</a>
</p>

## About

- Layout and style based on [this Figma](https://www.figma.com/file/7KP5bZBfhjeYz5YZdHT7Wh/Task%2FToDo-List?node-id=0%3A1)
- In this project I exercised some React and JS/TS concepts:
  - Passing props to components (using Typescript)
  - State (`useState`)
  - Side effects (`useEffect`)
  - Iterating in JSX (using unique keys such as `uuid`)
  - Arrays (`sort`, `reduce`, `map`)
  - Storing and fetching data from `localStorage`

## Requirements

- [Node.js LTS](https://nodejs.org/en/)
- `npm` or [`yarn`](https://yarnpkg.com/)
- [git](https://git-scm.com/)

## How to run

1. Clone the repo

   ```bash
   # Cloning with HTTPS
   git clone https://github.com/gusgalote/todo-react-ts.git

   # Enter the working dir
   cd todo-react-ts
   ```

2. Install dependencies

   ```
   yarn
   ```

3. Run `dev` script

   ```
   yarn dev
   ```

4. That's it! ✅ Dev server running by default @ http://localhost:5173/

## Made using

- [Yarn 1.x](https://yarnpkg.com/)
- [Vite](https://vitejs.dev/)
- [React](https://reactjs.org/)
- [Typescript](https://www.typescriptlang.org/)
- Icons by [`phosphos-icons`](https://phosphoricons.com/)

## Realização do Deploy
 Após conhecer varias tecnologias para realizar o deploy,
 escolhi fazer pelo vercel.
 Basicamente fiz o login na plataforma, com meu github após isso importei o repositório com a aplicação que desejava fazer o deploy,
logo a plataforma realizou toda a execução das atividades necessárias e me disponibilizou o link para minha aplicação.

Link da aplicação após realização do deploy: https://trainne-comp-jr-infra-vercel-liv4.vercel.app/
