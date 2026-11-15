# Statistics exercises (WS 2026)
This folder contains exercises for TU Wien course 231.028 "Methods and Models in Transport and Settlement Planning".

Each winter semester has its own branch (`2024_WS`, `2025_WS`, `2026_WS`, ...). This is the `2026_WS` branch.

### folder structure
Code and data are kept apart: all code is in this repository, all data goes in the `data` folder, sorted by lecture.

📂 TUW_231028
- 📄 README.md
- 📄 .gitignore
- 📄 exercise.ipynb: Lecture 4 exercise, for students less familiar with Python
- 📄 exercise_empty.ipynb: Lecture 4 exercise, for students already good with Python
- 📄 homework.ipynb: a small homework
- 📂 Lecture_3
  - 📄 descriptive_statistics.ipynb
  - 📄 regression_prepare.ipynb
  - 📄 regression.ipynb
  - 📄 discrete_choice.ipynb
  - 📄 discrete_choice_RUM.ipynb
  - 📄 transit_sim.py
- 📂 util
  - 📄 haversine.py: used to calculate haversine distance between two coordinates
- 📂 data *(not in this repository, download separately, see below)*
  - 📂 Lecture_3
    - 📄 README.md: data sources
    - 📂 regression_emission_data
    - 📂 vienna_gtfs
  - 📂 Lecture_4 (used by exercise and homework)
    - 📄 data_source.txt
    - 📂 GPS
    - 📂 survey_data
    - 📂 GTFS

### data
The data is not part of this repository. Download `Lecture_3.zip` and `Lecture_4.zip` from this [link](TODO_DATA_LINK_2026).
- **Locally:** unzip both into the `data` folder in the root of this repository, so you get `data/Lecture_3/...` and `data/Lecture_4/...`.
- **On Google Colab:** upload the zip file and run `!unzip -o Lecture_4.zip -d data` (or `Lecture_3.zip`). The first cells of each notebook show how.

### how to use
It is recommended to run the scripts on Google Colab:
* Exercise: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Institute-FVV/TUW_231028/blob/2026_WS/exercise.ipynb)
* Exercise (empty): [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Institute-FVV/TUW_231028/blob/2026_WS/exercise_empty.ipynb)
* Homework: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Institute-FVV/TUW_231028/blob/2026_WS/homework.ipynb)
