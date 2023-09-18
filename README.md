# CronVue

CronVue is a Node.js web application that provides a user-friendly interface for creating and managing scheduled cron jobs. It allows users to schedule and monitor cron jobs with ease.

## Features

- **Schedule Cron Jobs**: Easily create and schedule cron jobs with specific commands and cron expressions.

- **View Logs**: Monitor the output and logs of executed cron jobs.

- **Edit and Delete**: Modify or remove scheduled cron jobs as needed.

## Getting Started

These instructions will help you set up and run CronVue on your local machine.

### Prerequisites

Before you begin, ensure you have the following software installed:

- [Node.js](https://nodejs.org/) (v14 or higher)
- [npm](https://www.npmjs.com/)

### Installation

1. Clone the repository:

   ```
    git clone https://github.com/yourusername/CronVue.git
    cd CronVue

### Install dependencies:

    npm install

### Configure MongoDB:

Make sure you have a running MongoDB instance.
Edit the MongoDB connection settings in app.js to match your database configuration.

### Start the application:

    node app.js

CronVue should now be running locally. Access it in your web browser at http://localhost:3000.

### Usage
Visit the homepage to schedule new cron jobs.
View and manage your scheduled cron jobs on the /scheduled page.
Click "View Logs" to check the output of executed cron jobs.
Edit or delete cron jobs as needed.

### Deployment
To deploy CronVue to a production server, follow the same installation steps on your server. Additionally, consider using a process manager like PM2 for running your Node.js application in production.

### Contributing
Contributions are welcome! Please read CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests to us.

### License
This project is licensed under the MIT License - see the LICENSE.md file for details.

### Acknowledgments
Express.js: The web framework used in the project.
node-cron: Used for managing cron jobs.
MongoDB: The database used to store cron job data.

### Contact
If you have any questions or feedback, please contact us at smrithinns@yahoo.co.in.

Happy scheduling with CronVue!

