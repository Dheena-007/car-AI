
Car Sales Conversation Analyzer (CaroAI)

Welcome to CaroAI, a powerful tool for analyzing car sales conversations. This project is designed to help you extract key information from sales documents, visualize data, and understand trends in car sales.

 Overview

CaroAI offers a comprehensive solution for car sales analysis. It allows you to:
- Upload and analyze various document formats.
- Extract and compare customer data.
- Visualize data trends and generate insights.
- View descriptive statistics and popular car metrics.

 Features

- Document Upload and Analysis: Upload .txt, .pdf, or .csv files and analyze their content.
- Visualization: Generate visualizations for car sales trends, popular price ranges, and more.
- Statistics: Get descriptive statistics about car sales data.
- Comparison: Compare user data against existing datasets to identify trends and insights.

 Installation

To set up CaroAI locally, follow these steps:

1. Clone the Repository:
   ```bash
   git clone https://github.com/Dheena-007/car-ai.git
   cd caroai
   ```

2. Create a Virtual Environment:
   ```bash
   python -m venv venv
   source venv/bin/activate   On Windows use `venv\Scripts\activate`
   ```

3. Install Dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Download Data:
   Ensure that you have the `CarPrice.csv` file in the project directory. This file is required for data analysis and visualization.

 Usage

1. Run the Application:
   ```bash
   python app.py
   ```
   The application will start a local server at `http://127.0.0.1:5000`.

2. Upload Documents:
   - Use the file upload form to submit .txt, .pdf, or .csv files.
   - Click "Upload and Analyze" to process the file and extract information.

3. Compare Data:
   - Enter a user price and click "Compare Data" to visualize how it compares to the existing dataset.

4. View Data Visualization:
   - Click on various buttons to view visualizations such as most requested cars, popular price ranges, and more.

5. View Descriptive Statistics:
   - Click "View Descriptive Statistics" to get detailed statistics about the car sales data.

 Endpoints

- `GET /visualize`: Generate and return visualizations as a PNG image.
- `GET /statistics`: Provide data statistics and unique values as JSON.
- `GET /most-requested-cars`: Show the distribution of most requested cars.
- `GET /price-ranges`: Show popular price ranges.
- `GET /preferred-car-types`: Show preferred car types.
- `GET /common-objections`: Show frequently raised objections.
- `POST /compare`: Compare user data against existing datasets.
- `POST /`: Upload and analyze documents.

 Contributing

We welcome contributions to enhance CaroAI. To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.

Please ensure your code adheres to the project's style guide and includes appropriate tests.

 Contact

For any questions or feedback, please open an issue on GitHub or contact us at (mailto:jayasimmamomdad@gmail.com).

