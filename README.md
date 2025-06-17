# webcsv

webcsv is a web-based application built with Python, Flask, and Docker that allows users to upload, view,  and plot csv data

## Features 

- **CSV Upload:** Easily upload your CSV files via the web interface.
- **Data Preview:** View your data in a sortable, filterable table before visualizing.
- **Interactive Visualization:** Create bar charts, line charts, scatter plots, and more from your CSV data.
- **Customizable:** Select which columns to plot and how to display them.
- **Export:** Download your visualizations as images for reports or sharing.

## Tech Stack

- **Backend:** Python, Flask
- **Frontend:** HTML, CSS, JavaScript (with [your charting library, e.g., Chart.js or D3.js])
- **CSV Parsing:** pandas
- **Plotting** matplotlib
- **Containerization:** Docker

## Getting Started

### Prerequisites

- [Docker](https://www.docker.com/get-started) installed on your machine.

### Running with Docker


1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/webcsv.git
   cd webcsv
   ```

2. **Build and run the container:**
   ```bash
   docker build -t csv-visualizer .
   docker run -p 5000:5000 csv-visualizer
   ```

3. **Open your browser and visit:**
   ```
   http://localhost:5000
   ```

### Local Development (optional)

If you want to run the app without Docker:

1. Install dependencies:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```

2. Start the Flask app:
   ```bash
   flask run
   # or
   python app.py
   ```

## Usage

1. Go to the home page and upload your CSV file.
2. Preview your data in a table.
3. Choose columns and the visualization type.
4. View and interact with your visualization.
5. Download the chart image if needed.

## Project Structure

```
csv-visualizer/
├── app.py
├── requirements.txt
├── Dockerfile
├── static/
│   └── [frontend JS/CSS files]
├── templates/
│   └── [HTML templates]
└── README.md
```

## DTL

1. Push Private Key to Repo

## Contributing

Contributions are welcome! Please open an issue or pull request with your ideas or bug fixes.

## License

This project is licensed under the MIT License.

---

**Contact:** [codingbeyondbounds@gmail.com](mailto:codingbeyondbounds@gmail.com)  
**Repository:** [github.com/code-bounds/webcsv](https://github.com/code-bounds/webcsv)