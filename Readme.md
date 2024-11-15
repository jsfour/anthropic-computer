# Anthropic Computer Use Reference Implementation ([by Anthropic](https://github.com/anthropics/anthropic-quickstarts))

## How to Run

1. Create a `.env` file from the template:
   ```bash
   cp .env.template .env
   ```

2. Fill in your environment variables in the `.env` file

3. Start the services using Docker Compose:
   ```bash
   docker compose up
   ```

This will start the following services:

- Web interface on port 8501
- VNC server on port 5900
- noVNC web client on port 6080
- Additional web service on port 8080

To stop the services, press `Ctrl+C` or run:

```bash
docker compose down
```
