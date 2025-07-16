# Cyclistic Capstone Project

This is the final project of the **Google Data Analytics Professional Certificate**. The analysis focuses on usage trends among different types of Cyclistic bike-share customers, aiming to help the marketing team design strategies to convert casual riders into annual members.

---

## Case Study Summary

- **Business Task**: Identify trends in how annual members and casual riders use Cyclistic bikes differently, in order to support a marketing campaign aimed at converting casual riders into members.
- **Client**: Cyclistic (a fictional bike-share company based on real-world data from [Divvy/Motivate](https://divvybikes.com/system-data))
- **Analyst**: Rodrigo Willrich Gehlen
- **LinkedIn**: [linkedin.com/in/rwgehlen](https://www.linkedin.com/in/rwgehlen/)
- **Tools Used**:  
  - R  
  - tidyverse  
  - dplyr, ggplot2, lubridate  
  - R Markdown

---

## Data Source

This project uses the public Divvy bike trip data from 2019 and 2020.

You can download the raw datasets from:

- [Divvy Trip Data 2019](https://divvy-tripdata.s3.amazonaws.com/Divvy_Trips_2019_Q1.zip)
- [Divvy Trip Data 2020](https://divvy-tripdata.s3.amazonaws.com/Divvy_Trips_2020_Q1.zip)

Due to GitHub file size restrictions, the full datasets are not stored in this repository.

If you'd like to **run the code in the R Markdown file**, please download the datasets from the links above, unzip and place the `.csv` files into the data/ folder.

---

## Files in This Repository

| File | Description |
|------|-------------|
| `cyclistic_capstone_project.Rmd` | R Markdown file with full analysis |
| `cyclistic_capstone_project.html` | Rendered HTML version for easier viewing |
| `README.md` | This file |
| `data/` | Folder to store datasets |

---

## Key Analysis Steps

1. **Ask** – What do casual riders and annual members do differently?
2. **Prepare** – Loaded and explored historical bike-share datasets.
3. **Process** – Cleaned and formatted data to ensure consistency.
4. **Analyze** – Performed aggregations and visualizations.
5. **Share** – Created summaries, plots, and recommendations.
6. **Act** – Provided suggestions to the marketing team.

---

## Key Insights

- Casual riders peak on **weekends**, while members ride more on **weekdays**.
- **Trip duration** is generally longer for casual riders.
- **Marketing campaigns** targeting weekend casual users might help drive memberships.

---

## License

This project is open-source and available under the [MIT License](LICENSE).
