# REST-API-with-FastAPI-framework-in-python-and-mongodb

#Setup env

virtualenv venv


#For Linux/Mac

source venv/bin/activate

#For Windows

source venv/Scripts/activate

##Install package

pip install fastapi pymongo uvicorn


#Start server

uvicorn index:app --reload

