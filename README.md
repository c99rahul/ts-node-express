# TypeScript x Express x Node.js

This repository contains a basic TypeScript Express application that utilizes Node.js for server-side functionality. It is configured with Nodemon for automatic server restarts during development and uses ts-node for TypeScript execution.

If you are not familiar with a TypeScript workflow, consider checking out [the JavaScript branch](https://github.com/c99rahul/ts-node-express/tree/javascript) of this repository.

Feeling lost? Go through [the tutorial](https://blog.logrocket.com/how-to-set-up-node-typescript-express/) that this repository is built upon.

![Monitoring the Changes Detected By Nodemon](https://github.com/c99rahul/ts-node-express/assets/70071346/888bfc19-7034-4270-9696-04fc2b9fcb29)

## Prerequisites

Before you begin, ensure you have the following installed on your machine:

- [Node.js](https://nodejs.org/): Ensure that Node.js, preferably version 16 or higher, is installed on your system, as this project utilizes the latest versions of TypeScript and Nodemon.
- [npm](https://www.npmjs.com/): npm is the package manager for Node.js and comes with the Node.js installation.

## Installation

Clone the repository to your local machine:

```
git clone https://github.com/c99rahul/ts-node-express.git
```

Navigate to the project directory:

```
cd ts-node-express/
```

Install the project dependencies including TypeScript and Nodemon:

```
npm i
```

## Usage

For development purposes, you can run the application using Nodemon to automatically restart the server when changes are detected. Execute the following command:

```
npm run dev
```

This will start the server at `http://localhost:3000` by default. You can change the port in the `src/index.ts` file or create an `.env` file to manage the environt-specific variables separately.

For production, you can build the TypeScript files and then start the server. Run the following commands:

```
npm run build
npm start
```

## Project Structure

The project structure is organized as follows:

- `src`: Contains TypeScript source files
    - `index.ts`: Configures and starts the Express application
- `dist`: Output directory created during build for compiled TypeScript files
- `package.json`: Project configuration and dependencies
- `tsconfig.json`: TypeScript configuration

You can customize the project configuration i nthe `tsconfig.json` file and adjust the server settings in the `src/index.ts` file.

## License

This project is licensed under the MIT License - see the [LICENSE](/LICENSE) file for details.
