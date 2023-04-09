
![landing-page](/assets/images/landing-page.jpg)

# Module 11 Challenge Submission - Web Design Challenge

#### This repository contains the code and resources for the Weather Visualization Dashboard project, developed as part of Module 11 of the University of Western Australia's Data Analysis Bootcamp. The web application provides an interactive platform for exploring various weather visualizations and comparing weather factors across multiple locations.

## Table of Contents
- [Getting Started](#getting-started)
- [Web Application Features](#web-application-features)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [References](#references)

## Getting Started

These instructions will help you set up the project on your local machine for development and testing purposes.

### Prerequisites

Ensure you have Python 3.8+ installed on your system. You can check your Python version by running:

```python --version```

You will also need the following libraries:

- Pandas
- Bootstrap

## Web Application Features

The web application offers various features for visualizing and comparing weather data:

A homepage with an overview of the project and quick links to the different visualizations.
Four visualization landing pages, each containing a detailed plot and description for the following weather factors: Cloudiness, Humidity, Temperature, and Wind Speed.
A comparison page displaying all four plots in a grid format, allowing for easy comparison between the different weather factors.
A data page presenting the raw data used for the visualizations in a tabular format.

![comparison-page](/assets/images/comparison-page.jpg)

## Project Structure

```
Notebook
   |-- data-analysis.ipynb
   |-- table.html
Resources
   |-- .DS_Store
   |-- cities.csv
assets
   |-- .DS_Store
   |-- css
   |   |-- bootstrap.min.css
   |   |-- styles.css
   |-- images
   |   |-- Fig1.png
   |   |-- Fig2.png
   |   |-- Fig3.png
   |   |-- Fig4.png
   |   |-- comparison-page.jpg
   |   |-- landing-page.jpg
visualisations
   |-- cloudiness-landing.html
   |-- cloudiness.html
   |-- humidity-landing.html
   |-- humidity.html
   |-- temp-landing.html
   |-- temp.html
   |-- wind-landing.html
   |-- wind.html
README.md
comparison.html
data.html
index.html
```
## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Acknowledgments
I would like to thank our bootcamp instructors for their guidance and support throughout this assignment.

## References
- Python: https://www.python.org/
- Bootstrap: https://getbootstrap.com/
- Popper.js: https://popper.js.org/
- Font Awesome: https://fontawesome.com/
- University of Western Australia Data Analysis Bootcamp: https://bootcamp.ce.uwa.edu.au/data/



