# resume-evaluation-system

# How to run?

### STEPS:

Clone the repository

```bash
Project repo: https://github.com/rbi-international/resume-evaluation-system.git --- here use your repo name instead
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -p venv python=3.9 -y
```

```bash
source activate ./venv
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


### Create a `.env` file in the root directory and add your OPENAI_API_KEY credentials as follows:

```ini
OPENAI_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```


```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up localhost:
```


### Techstack Used:

- pandas
- nltk
- PyMuPDF
- python-docx
- sklearn

