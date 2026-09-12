# Permalist

A simple todo list built with Express, EJS, and PostgreSQL.

## Features

- View todo items
- Add items
- Edit items
- Delete items

## Requirements

- Node.js
- PostgreSQL

## Setup

1. Install dependencies:

   ```bash
   npm install
   ```

2. Create a PostgreSQL database named `permalist`.

3. Run `queries.sql` in that database to create and seed the `items` table.

4. Update the PostgreSQL connection details in `index.js` if needed.

5. Start the app:

   ```bash
   npm start
   ```

6. Open <http://localhost:3000>.
