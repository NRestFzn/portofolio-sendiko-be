## Prerequisites

- Node.js >= 20.x
- Mysql

## Module System

- By default, the `main` branch uses CommonJs (`type: commonjs`)
- For ES Module pending implementation because of Sequelize issue.

## Getting Started

1. **Clone the repository**

   ```bash
   https://github.com/NRestFzn/portofolio-sendiko-be.git
   cd portofolio-sendiko-be
   ```

2. **Set up environment variables**

   ```bash
   cp .env.example .env
   ```

   Then configure database settings in the `.env` file.

   or you can generate JWT secret key with command:

   ```bash
   npm run generate:secret
   ```

3. **Install dependencies**

   ```bash
   npm install
   ```

4. **Set up database**

   ```bash
   npm run db:create && npm db:reset
   ```

   Or create your database manually

5. **Start development server**

   ```bash
   npm run start
   ```

   With file watching:

   ```bash
   yarn watch:dev
   ```
