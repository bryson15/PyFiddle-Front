# PyFiddle Front-End - Running with Docker



## Production Version
- Available at [https://pyfiddle.net](https://pyfiddle.net)

## Running with Docker
### Step 1. Install and Run Docker Desktop
- Available at [https://www.docker.com](https://www.docker.com/products/docker-desktop/)

### Step 2. Clone the Repository
```powershell
git clone https://github.com/bryson15/PyFiddle-Front.git pyfiddle-frontend
cd pyfiddle-frontend
```

### Step 3. Build the Docker Image
```powershell
docker build -t pyfiddle-frontend .
```

### Step 4. Run the Docker Container
```powershell
docker run -p 3000:3000 pyfiddle-frontend
```

### Step 5. Visit Localhost:3000
- Available at [http://localhost:3000](http://localhost:3000)

### Step 6. Follow Back-End Instructions
- Available at [https://github.com/bryson15/](https://github.com/bryson15/PyFiddle-Back)

## Deploying to Pages
### Step 1. Build Project
```powershell
npm run build
```

### Step 2. Deploy Project
```powershell
npm run deploy
```