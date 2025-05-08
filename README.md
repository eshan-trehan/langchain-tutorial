# Local Setup
1. Create a .env file with the following details.
```
# Development Settings
AZURE_OPENAI_ENDPOINT=********
AZURE_OPENAI_API_KEY=********
AZURE_API_VERSION=********
AZURE_DEPLOYMENT=********
AZURE_EMBEDDING_MODEL=********
```
2. Install python virtualenv if not installed yet.
3. Setup your virtual environment.
```shell
python3 -m venv venv
```
4. Launch your Jupyter notebook.
```
# Activate your virtual environment
source venv/bin/activate
jupyter notebook
```
