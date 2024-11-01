# retrieval_system
# Information Retrieval from Multiple PDF 💁💬 with PaLM2


# How to run?
### STEPS:

Clone the repository

```bash
Project repo: [https://github.com/](https://github.com/fathi-hamed/retrieval_system)
```
### STEP 01- Create a virtual environment after opening the repository

```bash
pip install virtualenv 
```

```bash
python -m venv myenv
```
```bash
myenv\Scripts\activate```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

### Create a `.env` file in the root directory and add your GOOGLE_API_KEY as follows:

```ini
GOOGLE_API_KEY= "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```


```bash
# Finally run the following command
streamlit run app.py
```

Now,
```bash
open up : http://localhost:8501
```


### Techstack Used:

- Python
- LangChain
- Streamlit 
- PaLM2
- FAISS
