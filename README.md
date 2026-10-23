Trovio — A Modern Blogging & Publishing Platform

Trovio is a modern, feature-rich blogging and content publishing platform designed to empower writers to share their stories, ideas, and knowledge through a clean, intuitive, and visually appealing digital experience.

Built with modern web technologies, Trovio provides essential tools for creating, organizing, and publishing content while delivering a responsive experience across mobile devices and desktop screens.

✨ Features

- Rich Text Editor: Create and format engaging articles and blog posts using the integrated Tiny editor.
- User Authentication: Provides user registration, login, and account management through Appwrite.
- User Profiles: Give writers a dedicated identity and a place to showcase their published content.
- Tags & Categories: Organize articles by topics to improve content discovery and navigation.
- Responsive Design: Enjoy a consistent and accessible experience across mobile devices, tablets, and desktop computers.
- Modern UI: A clean interface built with React, Tailwind CSS, and Shadcn UI.
- Cloud Backend: Leverage Appwrite for authentication, database operations, and file storage.

🛠️ Technology Stack

Trovio uses a modern technology stack to deliver a maintainable and scalable web application.

Technology| Purpose
React| Frontend user interface
Tailwind CSS| Utility-first styling
Shadcn UI| Reusable interface components
Tiny Editor| Rich text content creation
Appwrite| Backend services, authentication, database, and storage
Vercel| Application deployment and hosting
Git| Version control

🚀 Getting Started

Follow these steps to set up Trovio in your local development environment.

Prerequisites

Before getting started, make sure you have the following installed:

- "Node.js" (https://nodejs.org/)
- npm or Yarn
- Git
- An Appwrite project with the required services configured

1. Clone the Repository

Clone the project repository to your local machine:

git clone <repository-url>

Navigate to the project directory:

cd Trovio

«Replace "<repository-url>" with the actual Git repository URL.»

2. Install Dependencies

Using npm:

npm install

Alternatively, using Yarn:

yarn install

3. Configure Environment Variables

Create a ".env" file in the project root directory and add the environment variables required by your application.

Example:

VITE_APPWRITE_ENDPOINT=your_appwrite_endpoint
VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
VITE_APPWRITE_DATABASE_ID=your_appwrite_database_id

Important: The variables above are examples. Confirm the exact variable names and configuration requirements in the project source code.

Replace the placeholder values with the appropriate configuration from your Appwrite project.

Never commit secret credentials, API keys, or private environment files to your public repository.

4. Start the Development Server

Run the following command:

npm run dev

The application will typically be available at:

http://localhost:5173

The exact port may vary depending on your project configuration.

☁️ Deployment

Trovio can be deployed using "Vercel" (https://vercel.com/).

General deployment steps:

1. Push the project to a Git repository.
2. Import the repository into Vercel.
3. Configure the required environment variables in the Vercel project settings.
4. Build and deploy the application.
5. Verify that the Appwrite endpoint, project configuration, authentication, and database services are working correctly.

Refer to the official "Vercel documentation" (https://vercel.com/docs) and "Appwrite documentation" (https://appwrite.io/docs) for detailed configuration instructions.

🏗️ Architecture

Trovio follows a frontend-and-backend architecture:

- Frontend: React, Tailwind CSS, and Shadcn UI power the user interface and content creation experience.
- Backend: Appwrite provides backend services, including authentication, database operations, and file storage.
- Deployment: Vercel hosts the deployed frontend application.

This architecture separates the user interface from backend services, helping keep the application organized and easier to maintain.

🤝 Contributing

Contributions are welcome!

If you would like to improve Trovio, fix bugs, or introduce new features, follow these steps:

1. Fork the repository.

2. Create a new branch:
   
   git checkout -b feature/your-feature-name

3. Make your changes and test them.

4. Commit your changes:
   
   git commit -m "Add: your feature description"

5. Push your branch:
   
   git push origin feature/your-feature-name

6. Open a Pull Request describing your changes.

Please ensure that your contributions are consistent with the project's existing code style and functionality.

🙏 Acknowledgements

Trovio builds on the work of the open-source community and the technologies that make modern web development possible.

Special thanks to the creators and maintainers of:

- "React" (https://react.dev/)
- "Tailwind CSS" (https://tailwindcss.com/)
- "Shadcn UI" (https://ui.shadcn.com/)
- "Appwrite" (https://appwrite.io/)
- "Vercel" (https://vercel.com/)

The project was initially developed by Siddhi.

📄 License

This project is presented as open source. Please check the repository for its license file and applicable terms before distributing or modifying the project.

---

Built for writers. Designed for stories. Powered by modern web technology.