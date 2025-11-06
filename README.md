Herl4ndos
.gitignore
https://rhapsody-h.id
from fastapi import FastAPI

app = FastAPI(title="Rhapsody_H API", version="0.1.0")

@app.get("/")
def root():
    return {"app": "Rhapsody_H", "status": "running", "features": ["dual_vocal", "genre_edit"]}
