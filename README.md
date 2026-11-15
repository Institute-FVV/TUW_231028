# Statistics exercises (WS 2026)
This folder contains exercises for TU Wien course 231.028 "Methods and Models in Transport and Settlement Planning".

Each winter semester has its own branch (`2024_WS`, `2025_WS`, `2026_WS`, ...). This is the `2026_WS` branch.

### folder structure
📂 TUW_231028
- 📄 README.md
- 📄 .gitignore
- 📄 exercise.ipynb: for students less familiar with Python
- 📄 exercise_empty.ipynb: for students already good with Python
- 📄 homework.ipynb: a small homework
- 📂 util
  - 📄 haversine.py: used to calculate haversine distance between two coordinates
- 📂 data *(download separately, see below)*
  - 📄 data_source.txt
  - 📂 GPS
    - 📄 GPS_trip1.csv
    - 📄 GPS_trip2.csv
  - 📂 survey_data
    - 📄 survey_data.csv
  - 📂 GTFS
    - 📄 agency.txt
    - 📄 calendar.txt
    - 📄 calendar_dates.txt
    - 📄 ...
- 📂 Lecture_3_data_and_code
  - 📄 descriptive_statistics.ipynb
  - 📄 regression_prepare.ipynb
  - 📄 regression.ipynb
  - 📄 discrete_choice.ipynb
  - 📄 discrete_choice_RUM.ipynb
  - 📄 transit_sim.py
  - 📂 data *(download separately, see below)*
    - 📂 regression_emission_data
    - 📂 vienna_gtfs

### data
The data is not part of this repository. It is stored externally at this [link](TODO_DATA_LINK_2026).
Download it and place each `data` folder at the location shown above. On Google Colab, upload the zip file to the notebook's working directory and unzip it there (see the first cells of each notebook).

### how to use
It is recommended to run the scripts on Google Colab:
* Exercise: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Institute-FVV/TUW_231028/blob/2026_WS/exercise.ipynb)
* Exercise (empty): [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Institute-FVV/TUW_231028/blob/2026_WS/exercise_empty.ipynb)
* Homework: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Institute-FVV/TUW_231028/blob/2026_WS/homework.ipynb)
