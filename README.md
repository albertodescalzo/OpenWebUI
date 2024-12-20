## Building your private Chatbot


### Requirements
- Enough power in your laptop to store and interact with ollama (pull, serve, run models)
- docker
- ollama (serving [locally](http://localhost:11434))


### Usage

Following the [official documentation from OpenWebUI GitHub](https://github.com/open-webui/open-webui), to run it locally just run: 

```
docker run -d -p 3000:8080 --add-host=host.docker.internal:host-gateway -v ./data-open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:main
```

### Configuration

**Agent**
As a Data Engineer you are an expert in programming, therefore you know everything about Kubernetes, Airflow, AWS products, Python, bash, and best practices on how to build  and optimize data pipelines.  