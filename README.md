
# College Attendance App

This College Attendance App is a desktop application designed to facilitate the management of student attendance for college classes. Built with VB.net and Microsoft SQL Server, this application offers a user-friendly interface for teachers and administrative staff to efficiently track and maintain attendance records.

## Features

- **User Authentication:** Secure login system for different user roles (admin, faculty, etc.).
- **Attendance Tracking:** Allows faculty to mark attendance for their classes and view historical data.
- **Report Generation:** Administrators can generate comprehensive attendance reports.
- **Manage Classes and Students:** Add, update, and delete student details and class information.

## Prerequisites

Before you install and run the College Attendance App, ensure you have the following installed:
- [Visual Studio](https://visualstudio.microsoft.com/downloads/) (2017 or later)
- [Microsoft SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)

## Installation

Follow these steps to get your development environment running:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Preyash-NEU/CollegeAttendanceApp.git
   ```

2. **Set up the SQL Server database:**
   - Open SQL Server Management Studio (SSMS).
   - Connect to your local SQL Server instance.
   - Execute the SQL scripts located in the `Database` folder of the cloned repository to create and populate the database.

3. **Open the project in Visual Studio:**
   - Open `CollegeAttendanceApp.sln` in Visual Studio.
   - Restore any NuGet packages if needed and rebuild the solution.

4. **Configure the database connection string:**
   - Navigate to `App.config` in the project files.
   - Update the connection string `CollegeDBConnectionString` with your SQL Server instance details.

5. **Run the application:**
   - Press `F5` or click on the `Start` button in Visual Studio to launch the application.

## Usage

To use the College Attendance App:
- **Login:** Enter your credentials to access the application. Default admin credentials are provided in the database setup script.
- **Mark Attendance:** Select the class and date, and mark attendance for students.
- **View Reports:** Generate and view attendance reports from the admin panel.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Your Name - [Your Email](mailto:your-email@example.com)

Project Link: [https://github.com/Preyash-NEU/CollegeAttendanceApp](https://github.com/Preyash-NEU/CollegeAttendanceApp)

