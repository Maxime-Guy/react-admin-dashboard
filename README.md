# React Admin Dashboard App

https://github.com/Maxime-Guy/react-admin-dashboard/assets/104865225/9a45eeb5-7694-4ac8-bb3d-6b5d95594140

This is a React-based administrator dashboard application that provides various data visualization components and features for managing and monitoring different aspects of your business or organization. The app is built using [Material-UI (MUI)](https://mui.com/), a popular React UI framework, and integrates several data visualization components, including bar charts, line charts, pie charts, geographical charts, and more.

## Features

- **Dashboard Overview**: Provides a high-level summary of key performance indicators (KPIs) such as emails sent, sales obtained, new clients, and traffic received. Visualized using StatBoxes and LineCharts.

- **Calendar Integration**: Includes an interactive calendar where you can manage and track events. Users can add, edit, and delete events on the calendar.

- **Invoices Management**: Allows users to view and manage a list of invoices with detailed information such as name, phone number, email, cost, and date.

- **Geographical Data Visualization**: Displays geographical data on a chart to help analyze and understand traffic patterns based on geography.

- **FAQ Section**: Provides a Frequently Asked Questions (FAQ) section to answer common queries and provide information to users.

- **Navigation**: Includes a sidebar for easy navigation to different sections of the application.

## Getting Started

To run the application locally, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Maxime-Guy/react-admin-dashboard.git
   ```

2. Navigate to the project directory:

   ```bash
   cd react-admin-dashboard
   ```

3. Install the dependencies using npm or yarn:

   ```bash
   npm install
   # or
   yarn install
   ```

4. Start the development server:

   ```bash
   npm start
   # or
   yarn start
   ```

5. To install all necessary compenents
   
   ```bash
   npm install @mui/material @emotion/react @emotion/styled @mui/x-data-grid @mui/icons-material react-router-dom@6 react-pro-sidebar@0.7.1 formik yup @fullcalendar/core @fullcalendar/daygrid @fullcalendar/timegrid @fullcalendar/list @nivo/core @nivo/pie @nivo/line @nivo/bar @nivo/geo
   ```

6. Open your web browser and visit [http://localhost:3000](http://localhost:3000) to access the application.

## Folder Structure

The project follows a modular folder structure for better organization:

- `src/components`: Contains reusable UI components used throughout the application.
- `src/data`: Stores mock data used for testing and development.
- `src/scenes`: Contains different sections of the application, including the dashboard, calendar, invoices, etc.
- `src/theme`: Defines the theme and color mode configurations using MUI's theming capabilities.
- `src/App.js`: The main application entry point, where routes and the theme provider are set up.
- `src/index.css`: Global CSS styles for the application.

## Dependencies

This project relies on several key dependencies, including:

- [React](https://reactjs.org/): A JavaScript library for building user interfaces.
- [Material-UI (MUI)](https://mui.com/): A popular React UI framework.
- [FullCalendar](https://fullcalendar.io/): A JavaScript event calendar library.
- [react-router-dom](https://reactrouter.com/): A routing library for React applications.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b feature-name`.
3. Make your changes and commit them with clear commit messages.
4. Push your changes to your fork: `git push origin feature-name`.
5. Create a pull request to the main repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

- [Maxime Guy Bakunzi](https://github.com/Maxime-Guy)

## Acknowledgments

- Special thanks to the [Material-UI](https://mui.com/) and [FullCalendar](https://fullcalendar.io/) teams for their excellent libraries.

Feel free to customize and enhance this dashboard application to meet your specific needs. Happy coding! 🚀
