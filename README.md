# Promptopia

Promptopia is a social platform for sharing and exploring AI Prompt ideas. Users can log in with their Google account, view their own profiles, explore profiles of others, and engage in a collaborative space for AI creativity.

This project is built with [Next.js](https://nextjs.org/) and bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Technologies Used

- [Next.js](https://nextjs.org/)
- [TailWind CSS](https://tailwindcss.com/docs/guides/nextjs)
- [MongoDB](https://www.mongodb.com)
- [Mongoose](https://mongoosejs.com/)
- [Google Cloud](https://cloud.google.com/)

## Features

- User authentication with Google account
- View and edit posts
- Share and explore AI Prompt ideas
- Main page showcasing popular AI Prompts

## Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/TihMalagutii/promptopia-project-nextjs.git
    cd promptopia-project-nextjs
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Set up environment variables:

    Create a `.env` file in the root of the project and add the following:

    ```env
    GOOGLE_CLIENT_ID=your-google-client-id
    GOOGLE_CLIENT_SECRET=your-google-client-secret
    MONGODB_URI=your-mongodb-uri
    GOOGLE_CLOUD_API_KEY=your-google-cloud-api-key
    ```

    Replace `your-google-client-id`, `your-google-client-secret`, `your-mongodb-uri`, and `your-google-cloud-api-key` with your actual credentials.

4. Run the development server:

    ```bash
    npm run dev
    ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.
