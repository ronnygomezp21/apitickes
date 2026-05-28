# STACK
## Runtime y Lenguaje
- Node.js 22.x (LTS)
- TypeScript 5.x (strict mode)

## Frameworks
- Express 4.x (HTTP)

## Librerias
- TypeORM 0.3.x (ORM)
- bcryptjs 3.0.x (Encriptacion)
- cors 2.8.x
- dotenv 17.4.x (Variables de entornos)
- jsonwebtoken 9.0.x (JWT)
- pg 8.20.x
- reflect-metadata 0.2.x 
- zod 4.4.x (validacion de campos de entrada)

## Compilacion y Ejecucion
- tsc (TypeScript Compiler oficial)
- tsx 4.x (solo desarrollo)

## Scripts estandar
- npm run dev -> entorno desarrollo
- npm run build -> compilacion TypeScript
- npm run start -> produccion
- npm run test -> pruebas

## Base de datos: PostgreSQL 16
## Testing: Jest + ts-jest
## Linting: ESLint + Prettier

## Tecnologias Prohibidas
- NestJS (usamos Express con Modular)
- JavaScript (usamos Typescript como lenguaje de programacion)
- Sequelize, Prisma (Solo TypeORM)
- MongoDB (Solo PostgreSQL)
- yarn (usamos npm exclusivamente)
