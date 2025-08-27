```bash
python -m venv .venv

# Linux
source .venv/Scripts/activate

# Windows
.\.venv\Scripts\activate

pip install -r requirements.txt

docker-compose up -d

uvicorn src.main:app --reload

or from advocare/ folder use "pnpm nx run ai-service:serve"

http://127.0.0.1:8000/docs#/


```
