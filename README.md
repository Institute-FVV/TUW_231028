# Statistics exercises (WS 2026)
This folder contains exercises for TU Wien course 231.028 "Methods and Models in Transport and Settlement Planning".

### folder structure
Code and data are kept apart, with one folder per lecture or homework in each: all code is in this repository, all data goes in the `data` folder.

📂 TUW_231028
- 📄 README.md
- 📄 .gitignore
- 📂 Lecture_3
  - 📄 descriptive_statistics.ipynb
  - 📄 regression_prepare.ipynb
  - 📄 regression.ipynb
  - 📄 discrete_choice.ipynb
  - 📄 discrete_choice_RUM.ipynb
  - 📄 transit_sim.py
- 📂 Lecture_4
  - 📄 exercise.ipynb: for students less familiar with Python
  - 📄 exercise_empty.ipynb: for students already good with Python
  - 📂 util
    - 📄 haversine.py: used to calculate haversine distance between two coordinates
- 📂 Homework_2
  - 📄 homework.ipynb
- 📂 data *(not in this repository, download separately, see below)*
  - 📂 Lecture_3
    - 📄 README.md: data sources
    - 📂 regression_emission_data
    - 📂 vienna_gtfs
  - 📂 Lecture_4
    - 📂 GPS
    - 📂 survey_data
  - 📂 Homework_2
    - 📄 data_source.txt
    - 📂 GTFS

### data
The data is not part of this repository. Download the zip file(s) you need from this [link](https://tuwienacat-my.sharepoint.com/:f:/g/personal/bingyu_zhao_tuwien_ac_at/IgBWO8jOZTScTa83kT5gGrP4AS8UhnW5wYVAjiJIdYOVc5k?e=52viGa):

| zip file | needed for |
|---|---|
| `Lecture_3.zip` | notebooks in `Lecture_3` |
| `Lecture_4.zip` | notebooks in `Lecture_4` |
| `Homework_2.zip` | notebook in `Homework_2` |

- **Locally:** unzip into the `data` folder in the root of this repository, so you get `data/Lecture_3/...`, `data/Lecture_4/...` and `data/Homework_2/...`.
- **On Google Colab:** the first cells of each notebook download and unzip the data automatically. If that fails, download the zip manually, upload it to Colab and run e.g. `!unzip -o Homework_2.zip -d data`.

### how to use
It is recommended to run the scripts on Google Colab.

Lecture 3:
* Descriptive statistics: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Institute-FVV/TUW_231028/blob/2026_WS/Lecture_3/descriptive_statistics.ipynb)
* Regression (preparation): [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Institute-FVV/TUW_231028/blob/2026_WS/Lecture_3/regression_prepare.ipynb)
* Regression: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Institute-FVV/TUW_231028/blob/2026_WS/Lecture_3/regression.ipynb)
* Discrete choice: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Institute-FVV/TUW_231028/blob/2026_WS/Lecture_3/discrete_choice.ipynb)
* Discrete choice (random utility): [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Institute-FVV/TUW_231028/blob/2026_WS/Lecture_3/discrete_choice_RUM.ipynb)

Lecture 4:
* Exercise: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Institute-FVV/TUW_231028/blob/2026_WS/Lecture_4/exercise.ipynb)
* Exercise (empty): [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Institute-FVV/TUW_231028/blob/2026_WS/Lecture_4/exercise_empty.ipynb)

Homework 2:
* Homework: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Institute-FVV/TUW_231028/blob/2026_WS/Homework_2/homework.ipynb)
