# Geographical Disparities and Service Distribution in Mental Health Treatment

## Description
This project aims to analyze the geographical disparities in the distribution of mental health services. We will investigate the availability and accessibility of mental health services across different regions, and how these disparities impact the mental health outcomes of the population.

## Goals
1. Identify regions with insufficient mental health service coverage.
2. Analyze the correlation between mental health service distribution and mental health outcomes.
3. Provide recommendations for improving mental health service accessibility in underserved areas.

## Repository Structure
- `data/`: Contains the datasets used in the analysis.
    - `mental_health_services.csv`: Data on the distribution of mental health services.
    - `mental_health_outcomes.csv`: Data on mental health outcomes by region.
- `notebooks/`: Contains Jupyter notebooks for data analysis and visualization.
    - `EDA_notebook.ipynb`: Exploratory Data Analysis notebook.
- `renv/`: Includes files to replicate the R environment using renv.
    - `activate.R`
    - `settings.dcf`
- `README.md`: Provides an overview of the project, instructions, and other relevant information.

## Setup Instructions
1. Clone the repository:
    ```sh
    git clone https://github.com/TheLiaoHu/Geographical-Disparities-and-Service-Distribution-in-Mental-Health-Treatment.git
    ```
2. Navigate into the repository directory:
    ```sh
    cd Geographical-Disparities-and-Service-Distribution-in-Mental-Health-Treatment
    ```
3. Load the renv environment:
    ```R
    renv::restore()
    ```
4. Open the EDA notebook:
    ```sh
    jupyter notebook notebooks/EDA_notebook.ipynb
    ```

## How to Interact with the Repository
- **Data Exploration**: Navigate to the `data/` directory to access the datasets used in the analysis.
- **Data Analysis**: Open the `EDA_notebook.ipynb` in the `notebooks/` directory to view and run the exploratory data analysis.
- **Environment Setup**: Ensure all necessary libraries are installed by restoring the renv environment using `renv::restore()`.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For questions or feedback, please contact [your-email@example.com](mailto:your-email@example.com).
