# Event Management

## Overview

Event Management is a comprehensive platform designed to streamline the planning, management, and execution of events. Whether you're organizing a small meetup or a large conference, our system provides the tools you need to ensure your event runs smoothly.

## Features

- **Event Creation**: Easily create and customize your events.
- **Participant Registration**: Manage participant registrations and track attendance.
- **Scheduling**: Create detailed event schedules with sessions, speakers, and venues.
- **Notifications**: Send reminders and updates to participants.
- **Feedback Collection**: Gather feedback from participants to improve future events.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (version 14.x or later)
- [MongoDB](https://www.mongodb.com/) (version 4.x or later)
- [Git](https://git-scm.com/)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AJ1206/Event-Management.git
   cd Event-Management
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Add the following variables:
     ```env
     DATABASE_URL=mongodb://localhost:27017/event_management
     PORT=3000
     JWT_SECRET=your_jwt_secret
     ```

4. Start the development server:
   ```bash
   npm start
   ```

5. Visit [http://localhost:3000](http://localhost:3000) in your browser to see the application in action.

## Usage

### Creating an Event

1. Navigate to the "Create Event" page.
2. Fill in the event details, including name, date, location, and description.
3. Click "Create" to save the event.

### Managing Participants

1. Go to the "Participants" section for your event.
2. View the list of registered participants.
3. Add, edit, or remove participants as needed.

### Scheduling Sessions

1. Access the "Schedule" tab for your event.
2. Add sessions, including titles, descriptions, and speakers.
3. Arrange the sessions in the desired order.

## Contributing

We welcome contributions to enhance the platform. To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Description of changes"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request with a detailed description of your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any inquiries or support, please contact us at [support@example.com](mailto:akshayjuluru004@gmail.com).
