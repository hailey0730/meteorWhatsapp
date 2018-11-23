##Partly follow the tutorial
`npm install -g ionic cordova`
`ionic start whatsapp`
- follow alone the instructions until done
- `ionic serve` to run

###realtime meteor server
- `npm install --save meteor-client-side` then import in main.ts
`meteor create api`
- remove client in api
- in api `npm link -s ../node_modules` to create symbolic link in api dir to accessible to root node modules
- remove .gitignore, package.json, package-lock.json in api
- in api `meteor add barbatus:typescript` to be able to use ts in meteor
- in api `mv server/main.js server/main.ts`
- create tsconfig.json in api
- in api `npm link -s ../src/declarations.d.ts`
- create declarations.d.ts in src
- back to root 'npm install --save `@types/meteor'
- 'npm install --save @types/underscore'
- 'npm install --save babel-runtime'
- 'npm install --save meteor-node-stubs'
- 'npm install --save meteor-rxjs'
- 'npm install --save meteor-typings'
- continue follow tutorial

create symbolic link fail