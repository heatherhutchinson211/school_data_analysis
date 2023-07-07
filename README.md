# Student Data Analysis Project

This project involves analyzing student data using the Python library Pandas. The project includes five deliverables for different aspects of the analysis, along with a summary of the key findings.

## Table of Contents

- [Project Overview](#project-overview)
- [Deliverables](#deliverables)
  - [Deliverable 1: Collect the Data](#deliverable-1-collect-the-data)
  - [Deliverable 2: Prepare the Data](#deliverable-2-prepare-the-data)
  - [Deliverable 3: Summarize the Data](#deliverable-3-summarize-the-data)
  - [Deliverable 4: Drill Down into the Data](#deliverable-4-drill-down-into-the-data)
  - [Deliverable 5: Compare the Data](#deliverable-5-compare-the-data)
- [Summary](#summary)
- [Usage](#usage)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This project focuses on analyzing student data to gain insights into their performance. The data analysis is performed using the Pandas library in Python. The dataset used for the analysis contains information about students' grades, test scores, and other relevant attributes.

## Deliverables

### Deliverable 1: Collect the Data

In this deliverable, the student data is collected and loaded into a DataFrame named `student_df`. The data file path is constructed using the `os.path.join` function, ensuring compatibility across different operating systems. The first five rows of the DataFrame are displayed to provide an initial glimpse of the data.

### Deliverable 2: Prepare the Data

For this deliverable, the student data is cleaned and prepared for analysis. Null values are removed from the DataFrame, and the `isna().sum()` function verifies that there are no remaining missing values. Duplicate entries are also eliminated, as confirmed by the `duplicated().sum()` function. The column types are displayed to provide an overview of the data types present in the DataFrame. Additionally, the "th" suffix is removed from the values in the "grade" column, which is then converted to an integer type.

### Deliverable 3: Summarize the Data

In this deliverable, the student data is summarized to extract key statistics. Summary statistics for the entire DataFrame are displayed, including measures like mean, standard deviation, minimum, maximum, and quartiles. The mean of the "math_score" column is specifically highlighted, along with storing the minimum reading score in the variable `min_reading_score`.

### Deliverable 4: Drill Down into the Data

This deliverable involves drilling down into specific subsets of the student data for in-depth analysis. The "grade" column is displayed to observe the distribution of grades. The first three rows of columns 3, 4, and 5 are displayed to provide a glimpse of the dataset's structure. Summary statistics are calculated specifically for 9th graders, and the row with the minimum reading score is isolated. Additionally, the reading scores of 10th graders at Dixon High School are examined. Finally, the average reading score for students in Grades 11 and 12 combined is calculated.

### Deliverable 5: Compare the Data

In this deliverable, the student data is compared and contrasted based on different factors. The average budget for each school type is displayed, providing insights into the financial resources available to different types of schools. The total number of students per school is presented in descending order, offering a perspective on school sizes. Finally, the average math scores are analyzed in relation to both the grade and school type combinations.

## Summary

After conducting the analysis on the student data, several interesting findings emerged. Notably, the average reading scores were almost identical between charter and public schools. However, there was a noticeable discrepancy in the average math scores, with a 4% difference. Additionally, the math scores appeared to decline as grades progressed in public schools, while remaining relatively consistent across different grades in charter schools.

To gain further insights, it would be beneficial to analyze reading scores based on grade as well. Additionally, investigating the relationship between school budget and test scores could provide valuable information.

## Usage

To use this project, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies mentioned in the installation section.
3. Run the project using your preferred Python environment.

## Installation

To install the necessary dependencies, run the following command:

```shell
pip install pandas
```

## Contributing

Contributions to this project are welcome. If you have any suggestions, improvements, or bug fixes, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
```

Feel free to further customize the content and structure of the README file to best fit your project.
