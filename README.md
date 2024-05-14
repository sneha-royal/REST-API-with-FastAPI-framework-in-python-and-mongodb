# REST-API-with-FastAPI-framework-in-python-and-mongodb

##Setup env
python -m venv fastapi

##activate environmaent
source venv/Scripts/activate

##nstall packages
pip install fastapi pymongo uvicorn

##start the server
uvicorn main:app --reload
