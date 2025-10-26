# 🐳 My Portfolio in Docker

This is a simple beginner Docker project that hosts a static HTML portfolio using **Nginx**.

## Run Locally
```bash
docker build -t my-portfolio .
docker run -d -p 8080:80 my-portfolio
