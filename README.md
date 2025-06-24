# gcbi_script

Gender Citation Balance Index (GCBI) Analyzer
This Python script computes the Gender Citation Balance Index (GCBI) for a list of academic authors, using their publications over the past 5 years. It retrieves citation data via the OpenAlex API and infers the gender of first and last authors in the cited papers to classify citation patterns into:

WW: Woman–Woman

WM: Woman–Man

MW: Man–Woman

MM: Man–Man


📦 Dependencies

Install these with pip install -r requirements.txt or manually:

tqdm
gender-guesser

gender-guesser is used for simple first-name-based gender inference. 

🧠 Usage
Add academic names to the academics list in the script:

academics = ["James B. Rowe", "David J. Whiteside"]
Run the script:

python gcbi_analyzer.py

Results will be saved as a CSV file (gcbi_results.csv) 
