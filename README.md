# Thinkboard

#### Live link:- https://thinkboard-mern-fbvx.onrender.com/

## Installation
### 1. Clone the repository

```bash
git clone https://github.com/codeIshan/thinkboard-mern.git
cd thinkboard-mern
```

### 2. Setup Backend


```bash
cd backend
npm install
```
Create a .env file inside backend/ with:
```bash
MONGO_URI= <mongodb+srv://<your-cluster-url>>
PORT=5001
UPSTASH_REDIS_REST_URL= <https://<your-upstash-url>.io>
UPSTASH_REDIS_REST_TOKEN= <your-upstash-token>
NODE_ENV=development
```

Run the server:
```bash
npm start
```
### 3. Setup Frontend

Open a new terminal:
```bash
cd frontend
npm install
npm start
```
<br/>

## Contributing

Contributions are welcome!

1. Fork the repo
2. Create a feature branch (feature-xyz)
3. Commit changes
4. Push and open a PR
