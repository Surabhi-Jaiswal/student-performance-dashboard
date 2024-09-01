🎓 Education Performance Dashboard

A comprehensive dashboard to analyze and visualize student performance data, enabling educators to identify trends, strengths, and areas for improvement. Built to support data-driven decision-making in educational institutions.

📊 Project Overview

The Education Performance Dashboard is designed to help educational institutions, teachers, and administrators monitor and assess student performance. The dashboard provides interactive visualizations and analytics, enabling users to drill down into key performance indicators (KPIs) such as grades, attendance, participation, and more.

Key Features:

- Data Visualization: Interactive charts and graphs to visualize student performance trends.
- Custom Filters: Apply filters based on subjects, grades, time periods, and more.
- Performance Comparison: Compare student performance across different classes, subjects, or demographics.
- Actionable Insights: Generate insights to help educators improve teaching strategies and student outcomes.
- Export Reports: Generate and export performance reports for further analysis.

🛠️ Technologies Used

- Frontend: React.js
- Backend: Python (Flask)
- Data Processing: Pandas, NumPy
- Visualization: Plotly, Dash
- Database: SQLite/PostgreSQL
- Deployment: Docker, Heroku

🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

Prerequisites:

- Python 3.8+
- Node.js and npm
- Docker (for containerized deployment)

Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/education-performance-dashboard.git
   cd education-performance-dashboard
   ```

2. Set up the virtual environment and install dependencies:

   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
   pip install -r requirements.txt
   ```

3. Install frontend dependencies:

   ```bash
   cd frontend
   npm install
   ```

4. Run the application:

   ```bash
   # In the backend directory
   flask run

   # In the frontend directory
   npm start
   ```

Deployment

To deploy the project using Docker:

1. Build and run the Docker container:

   ```bash
   docker-compose up --build
   ```

2. Access the application:

   Navigate to `http://localhost:5000` to view the dashboard.

📈 Usage

- Dashboard Navigation: Use the side navigation to explore different performance metrics.
- Custom Reports: Select filters to generate custom performance reports and export them as PDFs.
- Real-Time Updates: The dashboard updates data dynamically as new performance data is entered.

👥 Contributors

- [Surabhi Jaiswal] (https://github.com/Surabhi-Jaiswal) - Project Lead

📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

✨ Acknowledgements

- Special thanks to our mentors and collaborators for their guidance and support.
- This project was inspired by real-world educational challenges faced by institutions aiming for data-driven decision-making.
