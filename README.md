# The repo using POC build simple RAG concept
- tutorial reference: https://www.youtube.com/watch?v=WWUB7uqhKJk&t=133s

### Required tools
- python
- ollama (This repo using llama3.2 model)
- docker
- pgvector


### How to run pgvector in Docker

```sh
docker run -d --name pgvector-db -e POSTGRES_USER=myuser -e POSTGRES_PASSWORD=mypassword -e POSTGRES_DB=mydatabase -p 5432:5432 pgvector/pgvector:pg17
``

