# DashboardNetflix 📊

A data visualization dashboard for the Netflix dataset, built with Streamlit and Plotly, offering an interactive way to explore content trends and statistics.

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_white_red.svg)](https://dashboardnetflix-y7nfbkky3ryhyptz3crrde.streamlit.app/)

## 🚀 Live Demo

Access the live version of the dashboard here:
👉 **[https://dashboardnetflix-y7nfbkky3ryhyptz3crrde.streamlit.app/](https://dashboardnetflix-y7nfbkky3ryhyptz3crrde.streamlit.app/)**

## ✨ Key Features & Benefits

*   **Interactive Visualizations**: Dive deep into the Netflix dataset with dynamic and responsive charts powered by Plotly.
*   **Streamlined Interface**: Enjoy a clean and user-friendly web dashboard crafted with Streamlit, ensuring a smooth and intuitive exploration experience.
*   **Netflix Dataset Analysis**: Gain valuable insights into Netflix's movie and TV show catalog, including categories, release years, and more.
*   **Easy Deployment**: Leveraging Streamlit, the application can be quickly deployed and shared as a web app.
*   **Open Source**: Built entirely with popular Python libraries, making it accessible, understandable, and extensible for developers.

## 🛠️ Technologies Used

This project is built using the following core technologies:

### Languages
*   **Python**: The primary programming language used for all aspects of the application.

### Frameworks & Libraries
*   **Streamlit**: A powerful framework for creating interactive web applications and dashboards with Python.
*   **Pandas**: Essential for data manipulation, analysis, and processing of the Netflix dataset.
*   **Plotly**: Used for generating rich, interactive, and high-quality data visualizations.

## ⚙️ Prerequisites & Dependencies

To set up and run this project locally, you will need:

*   **Python 3.7+** installed on your system.
*   The specific Python libraries listed in the `requirements.txt` file:
    *   `pandas==2.2.3`
    *   `streamlit==1.44.1`
    *   `plotly==5.24.1`

## 🚀 Usage

After successfully installing the dependencies, you can launch the Streamlit dashboard:

1.  **Run the dashboard application:**
    From the root directory of the project (where `app.py` is located) and with your virtual environment activated, execute:
    ```bash
    streamlit run app.py
    ```

2.  **Access the Dashboard:**
    Streamlit will start a local server and provide you with a URL (typically `http://localhost:8501`). Open this URL in your web browser to access the dashboard.

3.  **Interact with the Dashboard:**
    Explore the various charts and visualizations. If implemented, use the sidebar filters to refine the data displayed and gain specific insights.

## 🛠️ Configuration Options

Currently, the `DashboardNetflix` project is designed for simplicity, with minimal external configuration.

*   **Data Source**: The dashboard loads its data directly from a public URL (`https://raw.githubusercontent.com/profzappa/profGit/refs/heads/master/netflix_titles.csv`) within the `app.py` file. To use a different dataset, you would need to modify the `pd.read_csv(...)` line in `app.py`.
*   **Dashboard Elements**: All visual components, including charts, filters, and layout, are defined programmatically within `app.py`. Customizations or additions to the dashboard's functionality require direct modification of the source code.

For future enhancements, external configuration files (e.g., YAML, JSON) or environment variables could be introduced to allow for easier customization of the data source or dashboard parameters without altering the core application logic.

## 📄 License

This project currently does **not have a specified license**.

This means that by default, all rights are reserved by the copyright holder (o0Junny0o), and you typically cannot use, distribute, or modify this software without explicit permission.

It is highly recommended that the project owner consider adding an open-source license (e.g., MIT, Apache 2.0, GPL) to clarify terms for contribution, use, and distribution.

## 🙏 Acknowledgments

*   The Netflix dataset utilized in this project is kindly provided and sourced from [profzappa/profGit](https://github.com/profzappa/profGit/blob/master/netflix_titles.csv).
*   A big thank you to the creators and maintainers of the fantastic open-source libraries: **Streamlit**, **Pandas**, and **Plotly**, which made this project possible.
