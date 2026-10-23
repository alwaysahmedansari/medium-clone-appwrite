Trovio — Modern Blogging & Content Publishing Platform

Trovio is a modern blogging and content publishing platform designed to provide writers with a clean, intuitive, and visually appealing space to share their stories, ideas, and knowledge.

Built with modern web technologies, Trovio combines a responsive user interface with powerful backend services to deliver a seamless content creation and publishing experience.

---

Key Features

- Rich Text Editor: Create, edit, and format articles using the integrated Tiny editor.
- Secure Authentication: Manage user registration and login through Appwrite authentication services.
- User Profiles: Provide writers with individual profiles to represent their identity and showcase their published content.
- Tags & Categories: Organize articles by topics for better content discovery and navigation.
- Responsive Design: Deliver a consistent user experience across mobile devices, tablets, and desktop screens.
- Modern User Interface: Built with React, Tailwind CSS, and Shadcn UI for a clean and intuitive design.
- Cloud Backend Services: Utilize Appwrite for authentication, database operations, and file storage.

---

Technology Stack

Trovio is built using modern technologies that support maintainability, performance, and an efficient development workflow.

Technology| Purpose
React| Frontend development
Tailwind CSS| Responsive styling and layout
Shadcn UI| Reusable UI components
Tiny Editor| Rich text editing and content creation
Appwrite| Authentication, database, and file storage
Vercel| Application deployment and hosting
Git| Version control and collaboration

---

Getting Started

Follow the instructions below to run Trovio in your local development environment.

Prerequisites

Before installing the project, ensure that you have the following:

- Node.js
- npm or Yarn
- Git
- An Appwrite account with the required backend services configured

1. Clone the Repository

Clone the repository to your local machine:

git clone <repository-url>

Navigate to the project directory:

cd Trovio

Note: Replace "<repository-url>" with the actual URL of your Git repository.

2. Install Dependencies

Using npm:

npm install

Alternatively, using Yarn:

yarn install

3. Configure Environment Variables

Create a ".env" file in the root directory of the project.

Add the environment variables required by your application. For example:

VITE_APPWRITE_ENDPOINT=your_appwrite_endpoint
VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
VITE_APPWRITE_DATABASE_ID=your_appwrite_database_id

Important: The variable names shown above are examples. Verify the exact names required by the existing source code before configuring your environment.

Replace the placeholder values with the appropriate configuration from your Appwrite project.

Security Notice: Never commit private credentials, secret API keys, or sensitive environment variables to a public repository.

4. Run the Development Server

Start the local development server:

npm run dev

Once the server starts, open the application in your browser:

http://localhost:5173

The default port may vary depending on the project configuration.

---

Architecture

Trovio follows a modern frontend-and-backend architecture designed to keep the application organized and maintainable.

Frontend

The frontend is built with React, Tailwind CSS, and Shadcn UI, providing a responsive interface and reusable components. The integrated Tiny editor supports rich text content creation.

Backend

Appwrite provides the backend infrastructure for user authentication, database operations, and file storage.

Deployment

Vercel is used to host and deploy the application, making it accessible to users through the web.

---

Deployment

Trovio can be deployed using Vercel.

Follow these general steps:

1. Push your project code to a Git repository.
2. Import the repository into your Vercel account.
3. Configure the required environment variables in your deployment settings.
4. Deploy the application.
5. Verify that authentication, database connectivity, and other backend services are working correctly.

For detailed instructions, refer to the official documentation:

- Vercel: https://vercel.com/docs
- Appwrite: https://appwrite.io/docs

---

Contributing

Contributions are welcome from developers who want to improve Trovio, fix bugs, or introduce new features.

To contribute:

1. Fork the repository.

2. Create a new branch:

git checkout -b feature/your-feature-name

3. Make your changes and test them.

4. Commit your changes:

git commit -m "Add: your feature description"

5. Push your branch:

git push origin feature/your-feature-name

6. Open a Pull Request with a clear description of your changes.

Please ensure that your contributions follow the existing project structure and coding conventions.

---

Acknowledgements

Trovio was initially developed by Siddhi and builds upon modern open-source technologies.

Special thanks to the developers and communities behind:

- React
- Tailwind CSS
- Shadcn UI
- Appwrite
- Vercel

Their tools and contributions help make modern web development more accessible and efficient.

---

License

Trovio is presented as an open-source project. Please refer to the repository's license file for the applicable terms of use, modification, and distribution.

If no license file exists, add an appropriate license before defining the project as open source.

---

Trovio — A Modern Space for Writers, Stories, and Ideas.