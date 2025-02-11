# Vercel Serverless API

## Overview
This project explores Vercel Functions and serverless architecture. The project is deployed on Vercel, utilizing its serverless function capabilities to handle API requests efficiently.

## Features
- Serverless API deployment using Vercel.
- Hosted frontend displaying available API endpoints.

## Building
This project is still under development.

## Getting Started
### Prerequisites
- Node.js.
- A Vercel account.

### Installation
1. Clone the repository:
   ```sh
   git clone <REPO_LINK>
   cd <folder_name>
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Run the development server:
   ```sh
   vercel dev
   ```

## Deployment
To deploy the project on Vercel, run:
```sh
vercel
```
Follow the on-screen instructions to complete the deployment.

## API Usage
### `/api/cors`
Enables CORS and forwards the request to the specified API URL.
Note: If the URL contains query parameters, make sure to properly encode them.
#### Example Usage:
```sh
GET /api/cors?apiUrl=https://dummyjson.com/users
```

## Learn More
- [Vercel Functions](https://vercel.com/docs/functions)
- [MDN URLSearchParams](https://developer.mozilla.org/en-US/docs/Web/API/URLSearchParams)
