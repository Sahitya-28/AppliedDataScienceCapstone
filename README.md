# IBM Applied Data Science Capstone Project

-----

## Table of Contents

1.  [About This Repository](https://www.google.com/search?q=%23about-this-repository)
2.  [Project Overview & Modules](https://www.google.com/search?q=%23project-overview--modules)
3.  [Key Technologies & Libraries](https://www.google.com/search?q=%23key-technologies--libraries)
4.  [How to Explore This Repository](https://www.google.com/search?q=%23how-to-explore-this-repository)
5.  [Project Outcomes](https://www.google.com/search?q=%23project-outcomes)
6.  [Attribution & Acknowledgements](https://www.google.com/search?q=%23attribution--acknowledgements)
7.  [Connect with Me](https://www.google.com/search?q=%23connect-with-me)

-----

## 1\. About This Repository

This repository showcases the final capstone project for the **IBM Data Science Professional Certificate** offered on Coursera. It details the end-to-end process of building a predictive model for SpaceX Falcon 9 first-stage landing outcomes, demonstrating practical data science skills from data collection and cleaning to machine learning model deployment.

The foundational problem statement, some initial data sources (like the SpaceX API and Wikipedia page), and project guidelines were provided by IBM/Coursera. However, **all code, analysis, visualizations, model implementations, and conclusions presented in this repository represent my original work and problem-solving.**

-----

## 2\. Project Overview & Modules

This capstone project involves a multi-stage approach to predict the success of Falcon 9 first-stage landings. The project is structured into several comprehensive modules, each building upon the previous one to culminate in a robust predictive model:

  * **Module 1: Data Collection & Wrangling**
      * Making GET requests to the SpaceX API to gather historical launch data.
      * Performing initial data cleaning, formatting, and handling missing values.
  * **Module 2: Web Scraping Falcon 9 Launch Records**
      * Extracting Falcon 9 launch records from a Wikipedia page using `BeautifulSoup`.
      * Parsing HTML tables and converting data into a Pandas DataFrame.
  * **Module 3: Exploratory Data Analysis (EDA) & Training Labels**
      * Conducting extensive EDA using visualization tools like `Matplotlib` and `Seaborn` to uncover patterns and correlations.
      * Identifying and labeling training data crucial for machine learning models.
  * **Module 4: Database Integration**
      * Loading the cleaned dataset into a `Db2` database to leverage SQL for structured querying and analysis.
      * Executing various SQL queries to derive insights related to launch data.
  * **Module 5: Feature Engineering & Visualization**
      * Creating new features from existing data to improve model performance.
      * Developing advanced visualizations to understand feature relationships and landing outcomes.
  * **Module 6: Interactive Visual Analytics with Plotly Dash**
      * Building an interactive web application using `Plotly Dash` for dynamic data exploration.
      * Incorporating user interaction components like dropdowns and sliders for intuitive analysis.
  * **Module 7: Machine Learning Models & Hyperparameter Tuning**
      * Standardizing the dataset and splitting it into training and test sets.
      * Applying various classification algorithms: Support Vector Machines (SVM), Decision Trees, Logistic Regression, and K-Nearest Neighbors (KNN).
      * Performing hyperparameter tuning using `GridSearchCV` to optimize model performance.
      * Evaluating each model's performance on test data to identify the best-performing model.

-----

## 3\. Key Technologies & Libraries

The following technologies and Python libraries were primarily utilized in this capstone project:

  * **Python 3**
  * **Jupyter Notebooks**
  * **Pandas** (Data manipulation and analysis)
  * **NumPy** (Numerical computing)
  * **Matplotlib** (Data visualization)
  * **Seaborn** (Statistical data visualization)
  * **BeautifulSoup** (Web scraping)
  * **Requests** (HTTP requests)
  * **Scikit-learn** (Machine learning: SVM, Decision Trees, Logistic Regression, K-Nearest Neighbors)
  * **Plotly & Dash** (Interactive web application development)
  * **`ipython-sql` / SQL Alchemy** (Database interaction with Db2)

-----

## 4\. How to Explore This Repository

To view and run the notebooks and code:

1.  **Directly on GitHub:** You can click on any `.ipynb` file in the `notebooks/` directory to view its rendered content directly in your browser.
2.  **Using GitHub Codespaces:** (Recommended for a full interactive environment without local setup)
      * Click the green "Code" button on this repository page, then select "Codespaces" and "Create codespace on main" (or your working branch). This will launch a cloud-hosted VS Code environment with all necessary dependencies.
3.  **Locally:**
      * Clone this repository: `git clone https://github.com/[YourGitHubUsername]/AppliedDataScienceCapstone.git`
      * Navigate into the cloned directory: `cd AppliedDataScienceCapstone`
      * (Optional but Recommended) Create and activate a virtual environment:
          * `python -m venv venv`
          * `.\venv\Scripts\activate` (Windows) or `source venv/bin/activate` (macOS/Linux)
      * Install the required libraries: `pip install pandas numpy matplotlib seaborn scikit-learn requests beautifulsoup4 plotly dash ibm_db` (adjust `ibm_db` based on your exact Db2 connector, if used).
      * Launch Jupyter Notebook: `jupyter notebook`
      * Open the `.ipynb` files from the `notebooks/` folder in your browser.

-----

## 5\. Project Outcomes

Through this capstone project, I successfully:

  * Demonstrated proficiency in collecting and wrangling data from various sources (APIs, web scraping).
  * Applied comprehensive EDA techniques to uncover insights from complex datasets.
  * Built and evaluated multiple machine learning models for classification tasks.
  * Utilized hyperparameter tuning to optimize model performance.
  * Developed an interactive dashboard for data visualization and exploration.
  * Showcased an end-to-end data science project workflow.

-----

## 6\. Attribution & Acknowledgements

I extend my profound appreciation to **IBM** and **Coursera** for developing and providing the **IBM Data Science Professional Certificate**. The structured curriculum, practical labs, and the challenging capstone project were instrumental in my data science learning journey. The core project idea, certain datasets, and template guidance for this capstone were provided as part of the course materials.

-----

## 7\. Connect with Me

I'm always open to discussing data science, machine learning, and new opportunities\!

  * **Email:** [sahityaatripathy@gmail.com]

-----
