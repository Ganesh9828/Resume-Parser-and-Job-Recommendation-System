# Resume-Parser-and-Job-Recommendation-System


## Overview

This project implements a **Resume Parser and Job Recommendation System** using machine learning techniques. It analyzes resumes, extracts relevant information, and recommends job categories based on the content of the resumes. The system is built using Python and utilizes libraries such as Pandas, Scikit-learn, and SpaCy.

## Features

- **Resume Parsing**: Extracts text from PDF and TXT files.
- **Data Analysis**: Analyzes resume datasets to categorize job roles.
- **Machine Learning Model**: Trains a Random Forest Classifier to predict job categories based on resume content.
- **Visualization**: Provides visual insights into the distribution of job categories and model performance metrics.
- **Skill Extraction**: Identifies key skills from resumes and matches them with job roles.

## Requirements

To run this project, ensure you have the following libraries installed:

```bash
pip install pandas matplotlib seaborn scikit-learn PyPDF2 spacy==3.5.3
python -m spacy download en_core_web_sm
```

## Getting Started

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd Resume-Parser-and-Job-Recommendation-System
   ```

2. **Mount Google Drive** (if using Google Colab):
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   ```

3. **Load the Dataset**:
   Ensure you have the dataset `UpdatedResumeDataSet.csv` uploaded to your Google Drive.

4. **Run the Jupyter Notebook**:
   Open `Resume Analysis.ipynb` in Jupyter Notebook or Google Colab and execute the cells sequentially.

## Usage

- **Resume Classification**: Upload a resume in PDF or TXT format to classify it into a job category.
- **Data Visualization**: Visualize the distribution of job categories and the performance of the machine learning model.
- **Skill Extraction**: Extract and analyze skills from resumes to match them with job descriptions.

## Example

After running the analysis on a sample resume, you will see outputs such as:

```
Predicted Category: Python Developer
```

And a detailed classification report showcasing the model's performance.

## Contributions

Feel free to contribute to this project by submitting issues or pull requests. 

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

For any questions or further information, please contact the project maintainer. Happy coding!
