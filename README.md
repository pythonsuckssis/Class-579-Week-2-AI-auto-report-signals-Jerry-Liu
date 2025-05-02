# AI Report Generator

A modern web application that transforms CSV data into concise, leader-friendly reports. The application processes report data and presents key metrics, changes, and blockers in a clean, single-page format with interactive visualizations.

![Report Generator Screenshot](screenshot.png)

## Features

- 📊 **Interactive Dashboard**: Clean, modern interface with real-time data visualization
- 📈 **Visual Analytics**: Bar charts and metrics cards for quick insights
- 📁 **Easy File Upload**: Drag-and-drop CSV file upload with visual feedback
- 🔄 **Real-time Processing**: Instant report generation with loading indicators
- 📱 **Responsive Design**: Works seamlessly on desktop and mobile devices

## Key Metrics Tracked

- Total Reports
- Reports Viewed by Leadership
- Unviewed Reports
- Positive Feedback Count
- Significant Changes
- Current Blockers and Risks

## Technical Stack

- **Backend**: Python/Flask
- **Frontend**: HTML5, JavaScript
- **Styling**: Tailwind CSS
- **Charts**: Chart.js
- **Data Processing**: Pandas

## Setup Instructions

1. Clone the repository:
```bash
git clone [your-repository-url]
cd [repository-name]
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run the application:
```bash
python app.py
```

5. Open your browser and navigate to `http://localhost:5000`