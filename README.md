from fastapi import FastAPI

app = FastAPI()

@app.get("/")
def read_root():
    return {"Hello": "World"}
# C-Users-mlanz-PycharmProjects-pythonProject2
hello world
