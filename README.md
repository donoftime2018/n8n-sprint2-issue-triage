# Course Stack — Week 2 Setup Record

## Environment
- Date: 8/31/2026
- Operating system and version: Windows/amd64 27.4.0
- Docker Desktop version: Docker Desktop 4.37.1 (178610)
- Git commit hash for this setup: 
    Client: bde2b89
    Server: 92a8393

## Service verification
| Service | Endpoint or command | Result | Evidence filename or safe note |
|---|---|---|---|
| Baserow | http://localhost:8080 |  |  |
| n8n | POST http://localhost:5678/webhook/stack-check-PranavRao | HTTP/1.1 200 OK
Content-Security-Policy: sandbox allow-downloads allow-forms allow-modals allow-orientation-lock allow-pointer-lock allow-popups allow-popups-to-escape-sandbox allow-presentation allow-scripts allow-top-navigation-by-user-activation allow-top-navigation-to-custom-protocols
Content-Type: application/json; charset=utf-8
Content-Length: 34
ETag: W/"22-6OS7cK0FzqnV2NeDHdOSGS1bVUs"
Vary: Accept-Encoding
Date: Mon, 31 Aug 2026 21:39:14 GMT
Connection: keep-alive
Keep-Alive: timeout=5

{"message":"Workflow was started"} | README.md created |
| ToolJet | http://localhost:3000 |  |  |
| labs Postgres | `docker compose exec labs-postgres psql -U student -d labs -c "SELECT version();"` |  |  |

## Local changes and troubleshooting
- Port changes made, if any:
- Problem encountered:
- Diagnostic command used:
- Resolution or current next step:

## Security check
- `.env` is ignored and was not committed: yes / no
- Screenshots and documentation were reviewed for secrets: yes / no
