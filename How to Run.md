## How to Run (WSL2)

### Step 1: Open WSL2 (Ubuntu)
Open **Ubuntu (WSL2)** from Windows Start Menu.
---
### Step 2: Clone the repository
```bash
git clone https://github.com/<your-username>/self-hosted-excalidraw-docker.git
cd self-hosted-excalidraw-docker
````
---
### Step 3: Start Excalidraw using Docker Compose
```bash
docker compose up -d
```
This will:
* Pull the official Excalidraw image
* Start the container in the background
* Expose the app on port **8080**
---
### Step 4: Access the application
Open your browser and go to:
```
http://localhost:8080
```
Excalidraw will load successfully.
---
### Step 5: Stop the application (when needed)

```bash
docker compose down
```
