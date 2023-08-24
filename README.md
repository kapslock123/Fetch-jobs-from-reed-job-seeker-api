
# Reed API Job Extractor

This repository contains a Jupyter notebook which interfaces with the Reed.co.uk job search API to fetch job listings based on specified criteria.

## **Table of Contents**

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## **Features**

- Interface with the Reed API to fetch job listings.
- Filter jobs based on specified areas and job titles (e.g., Frontend Developer, Data Analyst).
- Convert API responses to structured data for further analysis.

## **Installation**

1. Clone this repository.
2. Ensure you have the required libraries installed:
    - pandas
    - numpy
    - requests
3. You'll also need the custom module `reedsecrets` which should contain your authentication token for the Reed API.

## **Usage**

1. Open the Jupyter notebook: `reed api may 2023.ipynb`.
2. Update the `areas` and `courses` dictionaries if required:
    - `areas` maps broader regions to specific cities.
    - `courses` maps specific job roles to related job titles.
3. Set the desired job search parameters (`what` for job title and `where` for location).
4. Run the notebook cells to fetch and display the job listings.

## **License**

This project is licensed under the MIT License. See the [LICENSE.md](LICENSE.md) file for details.
