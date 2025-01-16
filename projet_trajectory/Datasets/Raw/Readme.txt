NewCaledonia Dataset
The NewCaledonia dataset comprises programs submitted in 2020 by a cohort of 60 students from the University of New Caledonia. These submissions were made on a programming training platform developed and maintained by the Computer Science department of the Orléans Technological Institute, part of the University of Orléans (France).

The complete dataset, labeled NewCaledonia_5690, contains 5,690 short Python programs created by beginner programming students across 66 different exercises.

Dublin Dataset
The Dublin dataset is a subset of the Azcona & Smeaton Dataset, which features student submissions from the University of Dublin collected between 2016 and 2019. While the original dataset, released in July 2020, includes nearly 600,000 programs in Python and Bash, this subset provides 42,487 programs, enriched semi-automatically with test cases.

Download the Dublin dataset here : https://www.dropbox.com/scl/fi/azb00ijabiuc56y06naim/dublin_42487.json?rlkey=6g1w257go5lsha47l6xnzrb54&e=1&dl=0

Data Format
Both datasets are available as two JSON files:

1. Dataset.json (e.g., NewCaledonia_5690.json)
A Python list where each entry is a dictionary representing a student's submission (an attempt). Each dictionary includes the following fields:

exercise_name: The exercise the attempt corresponds to (often used as a class label).

extension: The programming language of the submission (e.g., 'py' for Python).

date: The date and time the submission was made.

correct: Whether the platform evaluated the attempt as correct.

upload: The code submitted by the student.

user: A unique identifier for the student.

eval_set: The evaluation subset (training: 90%, validation: 5%, test: 5%).

aes0, aes1, aes2: Abstract Execution Sequences (AES) obtained by analyzing program execution traces at three levels of abstraction.

2. Dataset_exercises.json (e.g., NewCaledonia_exercises.json)
A Python list where each entry is a dictionary defining an exercise on the platform. Each dictionary contains:

solution: The reference solution provided by the instructor (if available).

funcname: The name of the function students were instructed to implement.

entries: A list of test cases, used for both evaluation and AES construction.

exo_name: A unique identifier for the exercise.