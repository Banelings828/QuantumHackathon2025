Hackathon project for quantum fall fest uOttawa.

Problem: Designing quantum feature maps for QML in order to analyze biological data. We chose a large data set of heart disease factors.

Approach: First, a QML was trained using the standard ZZFeatureMap and a smaller subset of the data (20%, 200 rows) as the large dataset was taking too long. Then, we created new feature maps and trained the 
QML on those to see if we could improve the accuracy of the QML's classifications.

How to run:

Setup:
- Download the notebook, or open it in a compatible web application
- Install qiskit, qiskit-machine-learning, scikit-learn onto the venv

Running:
- Run notebook sequentially
- Only run one of the following cells: Standard, Trial 1, Trial 2 or Trial 3 depending on what one wishes to test

Video Link: 
