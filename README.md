# CV Generator with Python

This project generates my professional CV using Python.

The objective is to create a reusable and structured CV generator based on my experience as a Senior Data Engineer, including cloud platforms, data engineering tools, programming languages, professional experience, education, certifications, and languages.

## About Me

My name is Kleber Albuquerque, and I am a Senior Data Engineer based in Portugal.

I have experience designing, building, and orchestrating scalable data pipelines using cloud-native technologies across Google Cloud Platform, Microsoft Azure, and AWS.

## Main Skills

- Python
- PySpark
- SQL
- Databricks
- Delta Live Tables
- Apache Airflow
- Cloud Composer
- BigQuery
- DataProc
- Dataflow
- Pub/Sub
- Azure Data Factory
- Azure Synapse
- Terraform
- GitLab CI/CD
- Power BI
- Tableau
- MicroStrategy

## Project Structure

```bash
cv-generator-python/
│
├── main.py              # Python script to generate the CV
├── cv_data.py           # CV information based on my professional profile
├── requirements.txt     # Project dependencies
├── README.md            # Project documentation
└── output/
    └── Kleber_Albuquerque_CV.pdf
```

## CV Sections

The generated CV includes:

- Personal Information
- Technical Skills
- Professional Experience
- Education
- Certifications
- Languages

## How to Run

Install the dependencies:

```bash
pip install -r requirements.txt
```

Run the project:

```bash
python main.py
```

The generated CV will be available in the `output/` folder.

## Example Technologies Used

```python
technologies = [
    "Python",
    "PySpark",
    "SQL",
    "Databricks",
    "Apache Airflow",
    "Google Cloud Platform",
    "Microsoft Azure",
    "BigQuery",
    "Terraform",
    "CI/CD"
]
```
education = [
    "MBA in Data Science — USP ESALQ",
    "Bachelor's Degree in Information Technology — University Ibirapuera"
]

certifications = [
    "Google Cloud Certified Digital Leader",
    "Databricks Certified Data Engineer Associate",
    "Apache Airflow Fundamentals – Astronomer",
    "Scrum Foundation Professional Certificate",
    "DevOps Essential Professional Certificate"
]

languages = {
    "Portuguese": "Native",
    "English": "Intermediate",
    "Spanish": "Intermediate"
}

## Author

**Kleber Albuquerque**  
Senior Data Engineer  
Portugal  
Email: klblima@gmail.com
