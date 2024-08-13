# Ask me anything

Fullstack project of a Forum. 
Used as a study case by Rocketseat Education.

# Initialization

### Server

To initialize the project, follow these steps:

1. At ***./packages/server***, run docker compose:

```bash
docker compose up
```

2. Run the migrations with the following command, in the same folder:

```bash
go run ./cmd/tools/terndotenv/main.go
```

3. Initialize server:

``` bash
go run ./cmd/wsrs/main.go
```

### Frontend
As the application is using React 19 RC, some dependencies need to be forced installation. 

1. Go to the directory ./packages/web and install all dependencies:
``` bash
npm install -f
```

2. Run the application
```bash
npm run dev
```