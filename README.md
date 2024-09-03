# GoalTracker

**GoalTracker** is an advanced project and task management solution designed to optimize team collaboration, track progress, and help achieve objectives with greater efficiency. Featuring role-based access, real-time progress monitoring, and detailed analytics, this tool is perfect for teams and managers seeking to improve workflow management and productivity.

---

## Key Features

### Core Functionality

- **Role-Based Access Control**:  
  - **Admin**: Oversee user management, team configuration, and platform settings.  
  - **Manager**: Initiate projects, allocate tasks, and track team progress.  
  - **Team Member**: Access and complete assigned tasks.

- **Project Management**:  
  - Define projects with start and end dates.  
  - Assign team members to specific projects.  
  - Monitor project progress in real-time based on task completion.

- **Task Management**:  
  - Create tasks with prioritized deadlines.  
  - Assign tasks to team members.  
  - Track task completion and overall progress using the new `value` feature to calculate weighted progress.

- **Notifications**:  
  - Get notifications for upcoming task deadlines and project updates.  
  - Alerts for overdue tasks and significant project milestones.

- **Analytics**:  
  - Gain insights into team and individual performance.  
  - Analyze task completion rates and track project progress trends.

---

## Technology Stack

| **Component**        | **Technology**             |  
|----------------------|----------------------------|  
| **Backend**          | Laravel (PHP)              |  
| **Frontend**         | Blade Templates            |  
| **Database**         | MySQL                      |  
| **Development Tools**| Docker, Composer, NPM      |

---

## Getting Started

To set up the project locally, follow these steps:

### Prerequisites

- PHP 7.4+
- Composer
- Node.js
- MySQL

### Installation Steps

1. **Clone the repository**:  
   ```bash
   git clone https://github.com/yourusername/goal-tracker.git
   cd goal-tracker

2. **Install backend dependencies**: 
   composer install

3. **Install frontend dependencies (Optional)**:
   npm install

4. **Set up the environment**:
   cp .env.example .env
   php artisan key:generate
   Update the .env file with your database credentials and other configurations.

5. **Run database migrations and seeders**:
   php artisan migrate --seed

6. **Start the development server**:
   php artisan serve

7. **Access the application**:
   Navigate to http://localhost:8000 in your web browser.

## Usage

### Admins:
- Add users (managers and team members) and configure platform settings.

### Managers:
- Create and assign projects to team members.
- Monitor task completion and adjust project goals as necessary.

### Team Members:
- View and manage assigned tasks.
- Update task statuses and provide progress reports.

## Future Enhancements

- **Calendar Integration**: Integrate with Google Calendar or Outlook for improved scheduling.
- **Mobile Application**: Develop a mobile-friendly version of the platform.
- **Advanced Analytics**: Introduce custom dashboards for deeper data insights.
