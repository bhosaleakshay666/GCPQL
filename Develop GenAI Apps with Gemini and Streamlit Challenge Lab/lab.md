
```bash
export REGION=
```

```bash
curl -LO raw.githubusercontent.com/bhosaleakshay666/GCPQL/refs/heads/master/Develop%20GenAI%20Apps%20with%20Gemini%20and%20Streamlit%20Challenge%20Lab/task1.sh
sudo chmod +x task1.sh
./task1.sh
```

***Click on given link & Test the app.***

***Press ```Ctrl + c``` for terminate.***


If App is not working then run this Below command 

```bash
cd generative-ai/gemini/sample-apps/gemini-streamlit-cloudrun
pip install google-cloud-aiplatform
python3 -m venv gemini-streamlit
source gemini-streamlit/bin/activate
python3 -m  pip install -r requirements.txt

streamlit run chef.py \
  --browser.serverAddress=localhost \
  --server.enableCORS=false \
  --server.enableXsrfProtection=false \
  --server.port 8080
```

```bash
curl -LO raw.githubusercontent.com/bhosaleakshay666/GCPQL/refs/heads/master/Develop%20GenAI%20Apps%20with%20Gemini%20and%20Streamlit%20Challenge%20Lab/task2.sh
sudo chmod +x task2.sh
./task2.sh
```

---
