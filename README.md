🩺 Diabetes Diagnosis System (C++)
This project is a console-based medical diagnosis tool written in C++. It simulates a step-by-step diagnostic process to assess the likelihood and type of diabetes a person may have, based on user input and symptom analysis.

📋 Features
Personal Information Intake Collects basic demographic and health data such as name, age, weight, height, and sex.

Three-Level Symptom Analysis The diagnosis is structured into three progressive levels:

Level 1: General symptoms (appetite, thirst, urination, vision, blood sugar, etc.)

Level 2: Secondary indicators (pancreatitis, carcinoma, cirrhosis, hormonal disorders)

Level 3: Chronic indicators (age group, body weight, symptom duration, autoantibodies)

Decision Logic Based on the input, the program determines:

Whether the person is diabetic

If the diabetes is primary or secondary

Whether it is insulin-dependent or non-insulin-dependent

Interactive Flow The user is prompted at each stage to proceed further based on the current diagnosis.

🛠️ Technologies Used
Component	Details
Language	C++
Libraries	<iostream>, <string>, <cctype>
Input Method	Console-based
Output	Text-based diagnosis
🚀 Getting Started
🔧 Prerequisites
A C++ compiler (e.g., g++, clang++)

A terminal or IDE that supports C++ (e.g., Code::Blocks, Visual Studio, or VS Code)

🧪 How to Run
Clone the repository:

bash
git clone https://github.com/siddharth9238/Diabetes-Analysis.git
cd Diabetes-Analysis
Compile the code:

bash
g++ -o diabetes Diabetes\ analysis.cpp
Run the executable:

bash
./diabetes
📌 Example Output
********* WELCOME *********
CAMPION SCHOOL
MEDICAL DIAGNOSIS SOFTWARE
DONE BY: Navi Arora
******** PRESS ENTER TO CONTINUE *********

PERSONAL INFORMATION
NAME: John Doe
AGE: 45
...
THE PERSON IS DIABETIC
PROCEED (Y/N)?
🤝 Contributing
Contributions are welcome! If you'd like to improve the logic, add new features, or refactor the code:

Fork the repository

Create a new branch (git checkout -b feature-xyz)

Commit your changes (git commit -m 'Add new feature')

Push to the branch (git push origin feature-xyz)

Open a Pull Request

📄 License
This project is open-source and available under the MIT License (add this if you include a license file).

🙌 Acknowledgments
Developed by Navi Arora as part of a school project.

Inspired by real-world medical diagnostic procedures.
