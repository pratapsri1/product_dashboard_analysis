pip install -r requirements.txt
#Novipro openrouter key
stremlit run app.py

.\proddashvenv\Scripts\python -m streamlit --version
.\proddashvenv\Scripts\python -m pip install -r requirements.txt

.\proddashvenv\Scripts\python -m streamlit run app.py --server.headless true --server.port 8501

python -m streamlit run app.py