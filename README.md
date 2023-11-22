## Auth API
## Installation and Usage
- Open GitBash
- Type `git clone git@github.com:Joseph-Barnett/02_auth.git`
- Cd into folder where you cloned the repo and type `code .`
- run `npm install` in terminal
- type `touch .env` and add this code to the file
```
DB_URL=postgres://aynliyux:vrRCEmZtg08JgezOtwDjj-vufKksdbFa@flora.db.elephantsql.com/aynliyux
PORT=3000
BCRYPT_SALT_ROUNDS=12
```
- run `npm setup-db` in terminal, this will link to the database
- run `npm run start` in terminal, you can access from links below
  ```
  Client side - http://127.0.0.1:5500/client/
  
  Server side - http://127.0.0.1:3000/posts
  -
  ```
  ## Current bugs

No bugs are currently known to me
