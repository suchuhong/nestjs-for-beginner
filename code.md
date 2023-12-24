## 1、基本概念

npm i -g @nestjs/cli
nest new nestjs-for-beginner
vscode 插件 thunder client

https://nest.nodejs.cn/

## 2、创建 module、service、controller

nest g module users
nest g service users
nest g controller users

https://docs.nestjs.com/first-steps
https://github.com/gitdagray/nestjs-course

https://docs.nestjs.com/controllers

## 3、认识 providers

https://docs.nestjs.com/providers

## 4、认识pipe、校验、抛出异常

npm install @nestjs/mapped-type
npm install class-validator
npm i class-transformer

https://docs.nestjs.com/pipes
https://github.com/typestack/class-validator#validation-decorators
https://docs.nestjs.com/techniques/validation

## 5、orm

### 配置数据库环境

npm i prisma -D
npx prisma init

编辑 schema.prisma
npx prisma migrate dev --name init
npx prisma migrate dev --name name_change

vscode 插件 Prisma

### 生成 database

nest g module database
nest g service database

### 生成 employees

nest g resource employees

Neon: https://neon.tech/
Prisma: https://www.prisma.io/
https://www.prisma.io/docs/getting-started/quickstart

## 6、CORS、限流、日志、异常

### CORS

https://docs.nestjs.com/faq/global-prefix
https://docs.nestjs.com/security/cors

### 限流

npm i --save @nestjs/throttler

https://docs.nestjs.com/security/rate-limiting

### 日志

https://docs.nestjs.com/techniques/logger

nest g module my-logger
npm g module my-logger

### 异常过滤器

https://docs.nestjs.com/exception-filters
