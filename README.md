# Django based web application for CSV upload

This is a Django-based web application that allows users to upload CSV files, perform data analysis using Pandas and NumPy, and display the results and visualizations on a web interface.

## Requirements

- Python
- Django
- Pandas
- NumPy
- Matplotlib
- Seaborn

1. **Create a virtual environment**:
   To create an environment:  python -m venv venv
   To activate environment: .venv/bin/activate  

2. **Install dependencies**:
    pip install django
    pip install pandas numpy matplotlib seaborn

3. **Apply migrations**:
    python manage.py migrate

4. **Run the development server**:
    python manage.py runserver

5. **Access the application**:
    Open your web browser and go to `http://127.0.0.1:8000/`.

6. On web browser, upload csv file

![alt text](<Images/Screenshot 2024-08-02 171236.png>)
![alt text](<Images/Screenshot 2024-08-02 171254.png>)
![alt text](<Images/Screenshot 2024-08-02 171320.png>)