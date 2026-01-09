# ORM

## Installation
Install the npm package:

npm install typeorm

You need to install reflect-metadata shim:

npm install reflect-metadata

and import it somewhere in the global place of your app (for example in app.ts):

import "reflect-metadata"

You may need to install node typings:

npm install @types/node --save-dev

Install a database driver: see the documentation for each particular driver: mongodb, mssql, mysql/mariadb, oracle, postgres, sap, spanner, sqlite.

## TypeScript configuration

Also, make sure you are using TypeScript version 4.5 or higher, and you have enabled the following settings in tsconfig.json:

"emitDecoratorMetadata": true,
"experimentalDecorators": true,