# Ask me anything

Fullstack project of a Forum. <br />
Used as a study case by Rocketseat Education.

<img width="1311" alt="image" src="https://github.com/user-attachments/assets/735929ee-60bc-404a-9b04-8861c6c65de9">

<img width="1363" alt="image" src="https://github.com/user-attachments/assets/6b472eec-8d48-46d0-b46a-c5db11ff2814">


# Initialization

### Server

To initialize the project, follow these steps:

1. At **./packages/server**, run docker compose:

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

1. Go to the directory **./packages/web** and install all dependencies:
``` bash
npm install -f
```

2. Run the application
```bash
npm run dev
```
