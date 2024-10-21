# Sales Dashboard

This project is a **Sales Dashboard** built using **Streamlit**, **Plotly**, and **Pandas**. It reads data from an Excel file and allows the user to filter sales data by city, customer type, and gender. The dashboard provides insights such as total sales, average rating, and sales by product line and hour. 

## Features

- Filter sales data by **City**, **Customer Type**, and **Gender**.
- Display key metrics:
  - **Total Sales**
  - **Average Rating** with star visualization
  - **Average Sales per Transaction**
- Visualize:
  - **Sales by Product Line** using a horizontal bar chart
  - **Sales by Hour** using a bar chart
- Responsive layout with charts displayed side-by-side.
- Hides unnecessary UI elements like the Streamlit menu, header, and footer.

## Installation

### Prerequisites

Make sure you have the following installed:

- Python 3.x
- [pip](https://pip.pypa.io/en/stable/)

### Libraries

Install the required libraries using the following command:

```bash
pip install streamlit pandas plotly openpyxl
