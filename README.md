# Task Management System  

A simple and efficient task management system built with [Next.js](https://nextjs.org/). This project is designed to streamline task handling for individual users and teams, providing features such as authentication, role-based access, and task tracking with drag-and-drop functionality.  

## Features  

### Authentication  
- Secure login system with password encryption.  
- JSON Web Tokens (JWT) for secure and persistent authentication.  

### Task Management  
- Create, read, update, and delete (CRUD) operations for tasks.  
- Tasks can be moved between states using drag-and-drop functionality.  
- Users can comment on tasks.  

### Role-Based Access Control  
- **Regular Users**:  
  - Access a personal dashboard displaying their tasks and group tasks.  
  - Comment on tasks and change their state using drag-and-drop.  
- **Administrators**:  
  - Manage users, tasks, and groups with full CRUD operations.  

### Database  
- Built with [Prisma](https://www.prisma.io/) as the ORM.  
- Uses SQLite as the database for simplicity.  

### Groups  
- Tasks can be assigned to groups for better organization.  

## Getting Started  

### Prerequisites  
- Node.js (v16 or later)  
- npm or yarn  

### Installation  
1. Clone this repository:  
   ```bash  
   git clone https://github.com/your-username/task-management-system.git  
   cd task-management-system  

2. Install dependencies
    ```bash 
    npm install  
    # or  
    yarn install  

3. Create a .env file in the root directory with the following variables
    ```bash 
    DATABASE_URL="file:./dev.db"  
    JWT_SECRET="your_jwt_secret"  

4. Run the Prisma migrations
    ```bash 
    npx prisma migrate dev  

5. Start the development server
    ```bash 
    npm run dev  
    # or  
    yarn dev  


