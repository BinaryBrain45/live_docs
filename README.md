# Real-Time Collaborative Document Editor

This project is a real-time collaborative document editing application built using Next.js, TypeScript, Tailwind CSS, and other modern web technologies. The application allows multiple users to edit documents simultaneously, comment, and manage users in real-time.

## Features

- **Real-Time Collaboration**: Users can edit documents simultaneously with real-time updates.
- **Commenting System**: Users can leave comments on specific sections of the document.
- **User Management**: Authentication and user management are integrated to control access.
- **Responsive Design**: The application is fully responsive, providing a seamless experience on all devices.
- **Deployment**: The application is deployed using Netlify, ensuring a fast and reliable hosting environment.

## Live Site

The application is live and can be accessed at: [livedocs545.netlify.app](https://livedocs545.netlify.app).

## Technology Stack

- **Next.js**: A React framework for building web applications.
- **TypeScript**: A typed superset of JavaScript, adding static types.
- **Tailwind CSS**: A utility-first CSS framework for rapid UI development.
- **Liveblocks**: An open-source library for building real-time collaborative applications.
- **Clerk**: An authentication platform for web applications.
- **Netlify**: A platform for deploying static and serverless web applications.

## Tools Used

- **Visual Studio Code**: The code editor used for development.
- **GitHub**: Version control and project repository.
- **Netlify**: The platform used for deployment.

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- A Clerk account for authentication
- A Netlify account for deployment

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/BinaryBrain45/live_docs.git
    cd live_docs
    ```

2. **Install dependencies:**

    ```bash
    npm install
    # or
    yarn install
    ```

3. **Set up environment variables:**

    Create a `.env.local` file in the root directory and add the necessary environment variables for Clerk and Liveblocks.

    ```plaintext
    NEXT_PUBLIC_CLERK_FRONTEND_API=<your-clerk-frontend-api>
    CLERK_API_KEY=<your-clerk-api-key>
    NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=<your-liveblocks-public-key>
    ```

4. **Run the development server:**

    ```bash
    npm run dev
    # or
    yarn dev
    ```

    Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

### Deployment

1. **Deploy to Netlify:**

    Connect your GitHub repository to Netlify and deploy your application. Netlify will automatically handle the build process and provide a live URL.

    The application is deployed and accessible at: [livedocs545.netlify.app](https://livedocs545.netlify.app).

    For more details, refer to the [Netlify documentation](https://docs.netlify.com/).

## Contributing

If you'd like to contribute to this project, please fork the repository and create a pull request. Contributions are welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the developers of Next.js, TypeScript, Tailwind CSS, Liveblocks, Clerk, and Netlify for creating such awesome tools.
