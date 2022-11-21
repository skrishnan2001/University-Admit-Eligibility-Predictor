## Steps to run the Streamlit app
- Install the required dependencies with the command:
```
pip install -r requirements.txt
```

- Replace line 128 in app.py with your IBM Cloud API KEY
```
128. API_KEY = "<Your API-KEY>"
```

- To run the web app locally, execute the command:
```
streamlit run app.py
```

- The app will be running in the browser. If not, go to the web browser and type:
```
localhost:8051
```


### Alternatively to use the containerized project, follow the steps
- Build the docker image
```
docker build -t <img_name> .
```

- Build container and run the application locally
```
docker run -p <port>:<port> <img_name>
```

- You can access the containerized application in 
```
localhost:<port>
```
