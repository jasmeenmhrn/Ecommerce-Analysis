#Setup Environment

conda create --name main-ds python=3.9
conda activate main-ds
pip install numpy pandas scipy matplotlib seaborn jupyter streamlit babel

#Run Streamlit App

streamlit run submission_project_dicoding.py