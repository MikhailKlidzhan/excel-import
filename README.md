# Excel import app

## Setup

1. **Clone the repo to your machine:**

```bash
git clone https://github.com/johniehuge/excel-import.git
cd excel-import
```

2. **Create .env with this data:**

```bash
cp .env.template .env
```

**Inside .env:**

```
DB_NAME=xlimportdb
DB_USER=admin
DB_PASSWORD=admin
DB_HOST=db
DB_PORT=5432
```

3. **Launch a docker container:**

```bash
docker-compose up --build
```

## Project Goals

This project demostrates:

- Backend design with <span style='background-color: blue;'>**Django**</span>
- Frontend design with <span style='background-color: blue;'>**Bootstrap/JQuery**</span>
- .xlsx files handling using <span style='background-color: blue;'>**pandas**</span>
