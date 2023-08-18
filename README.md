# Bosch Project 
https://bosch-frontend.azurewebsites.net/ <br>
## Introduction <br>
Determining the price to set for Bosch products depending on customer sentiments provided from online shopping platforms such as Lazada and Shopee by using NLP. This project was done in Dec 2020 - Feb 2021 along with other teammates under the NTU Edge programme.

## Local Setup

### Backend

Available on `localhost:8000`.

```
poetry install # download dependencies
poetry shell # activate virtual environment
uvicorn api:app --reload # run server (dev)
python api.py # run server (prod)
```

### Frontend

Available on `localhost:3000`.

```
npm install
npm run start
```