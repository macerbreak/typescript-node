# typescript-node
Typescript node
-D - install packages for dev dependencies
--save - install packages for dependencies
1) npm init -y
2) npm install --global yarn
3) add index.ts into your project
4) yarn add express --save
5) yarn add typescript ts-node -D
6) yarn add @types/express -D
7) yarn add @types/node -D
8) yarn add nodemon -D
9) rename index.ts to index.ts
10) yarn tsc --init
11) find in tsconfig.json "outDir" value and set path for your ts files that will be compiled (after yarn tsc) in js files
12) yarn tsc -w (typescript in watch, real time mode)
13) add scripts for your dependencies: "scripts":{"watch":"tsc -w", "dev":"nodemon ./dist/index.js"}