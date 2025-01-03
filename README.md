# Next.js Project Management Application

A **full-stack project management application** designed to help teams manage projects, tasks, and progress effectively. Built using **Next.js**, **Node.js**, and various **AWS services** for cloud hosting and authentication.

## Live Demo

You can try out the deployed version of the application here:  
[**Live Project Demo**](https://main.d2qrsxg8uodtlg.amplifyapp.com)

## Tech Stack

- **Frontend**:

  - **Next.js** (React framework for SSR and static site generation)
  - **Tailwind CSS** (Utility-first CSS framework for responsive design)
  - **Redux Toolkit** (State management)
  - **Redux Toolkit Query** (Data fetching and caching)
  - **Material UI Data Grid** (Data visualization and grid components)

- **Backend**:

  - **Node.js** (JavaScript runtime)
  - **Express.js** (Web framework for handling API requests)

- **Database**:

  - **PostgreSQL** (Relational database)
  - **Prisma** (ORM for database management)
  - **pgAdmin** (Database administration tool)

- **Cloud Services**:
  - **AWS EC2** (Virtual servers for hosting the app)
  - **AWS RDS** (Manage PostgreSQL database)
  - **AWS API Gateway** (API management and integration)
  - **AWS Amplify** (Frontend hosting and continuous deployment)
  - **AWS S3** (Storage for static files and media)
  - **AWS Lambda** (Serverless functions)
  - **AWS Cognito** (User authentication and management)

## Features

- **Task Management**:  
  Easily create, assign, and track tasks for team members to ensure everything gets done on time.

- **Project Planning**:  
  Define project goals, milestones, and deadlines to improve project clarity and keep your team on track.

- **Customizable Dashboards**:  
  Personalize your project dashboards to focus on key tasks, deadlines, and team activity for better productivity.

- **Task Prioritization**:  
  Prioritize tasks using labels, due dates, and urgency levels to keep things organized and avoid bottlenecks.

- **Progress Tracking**:  
  Track progress on tasks and projects through visual indicators like completion bars and status updates.

- **Multi-Project Management**:  
  Efficiently manage and switch between multiple projects from a single, unified dashboard.

- **Cloud Integration with AWS**:  
  Leverage the power of AWS to ensure scalability, security, and reliability, including storage, hosting, and serverless functions.

- **Responsive UI**:  
  Fully responsive and accessible across all devices, from desktop to mobile, with a clean, user-friendly interface.

- **Data Security**:  
  Ensure your team's data is protected with secure authentication and user management powered by AWS Cognito.

## Installation Steps

Follow these instructions to set up and run the project locally.

1. **Clone the repository**:

   Start by cloning the repository to your local machine:

   ```
   git clone https://github.com/ArmanWain/nextjs-project-management-app.git
   cd nextjs-project-management-app
   ```

2. **Configure environment variables**:

   You need to create and configure two `.env` files for server and client settings.

   - **Server-side** `.env`: Configure the server settings, such as the port and database URL.

     ```bash
     PORT=8000
     DATABASE_URL=your_database_url_here
     ```

   - **Client-side** `.env.local`: Set the following environment variables to configure client settings.

     ```bash
     NEXT_PUBLIC_API_BASE_URL=http://localhost:8000
     NEXT_PUBLIC_COGNITO_USER_POOL_ID=your_user_pool_id_here
     NEXT_PUBLIC_COGNITO_USER_POOL_CLIENT_ID=your_client_id_here
     ```

   Make sure to replace the placeholders with your actual values.

3. **Install dependencies for both client and server**:

   Next, install the necessary dependencies for the client and server:

   ```
   cd client
   npm i
   cd ..
   cd server
   npm i
   ```

4. **Run the project**:

   Finally, start the development server to run the project locally:

   ```
   npm run dev
   ```
