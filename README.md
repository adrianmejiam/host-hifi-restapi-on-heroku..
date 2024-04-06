<p align="center">
 <img width="100px" src="https://github.com/sachinsenal0x64/picx-images-hosting/raw/master/heroku-software-deployment-software-development-postgr.7p22o7na4.webp" align="center" alt=":package: deploy-hifi-restapi-on-vercel" />
 <h2 align="center">:package: Host HiFi REST API ON Heroku</h2>
</p>

<div align="center">
 
   #### This is [Hifi Tui](https://github.com/sachinsenal0x64/hifi-tui) core it base on this API and you can selfhost :)
   
 </div>

<br><br>

# :two_hearts: Community

> :beers: Join the community:  <a href="https://discord.gg/EbfftZ5Dd4">Discord</a>
> [![](https://cdn.statically.io/gh/sachinsenal0x64/picx-images-hosting@master/discord.72y8nlaw5mdc.webp)](https://discord.gg/EbfftZ5Dd4)

<br>

# ❓ Requirements
> [!TIP]
> You can access reverse [api](https://github.com/sachinsenal0x64/Hifi-Tui?tab=readme-ov-file#-tidal-reverse-api--status) for free.

- Tidal Subscription

- Fill the [.env](https://github.com/sachinsenal0x64/host-hifi-restapi-on-heroku/blob/main/env-example)

- Redis (its free)

- Grab Tokens / Ids Using [tidal_auth.py](https://github.com/sachinsenal0x64/hifi-tui/blob/main/tidal_auth/)
 
<br>

# ☁️ One-Click Deploy To Heroku
> ⛓️‍💥 THIS WILL BYPASS GEO RESTRICTED CONTENT 
<a href="https://heroku.com/deploy?template=https://github.com/sachinsenal0x64/host-hifi-restapi-on-heroku" alt="Deploy to Heroku">
     <img width="150" alt="Deploy" src="https://www.herokucdn.com/deploy/button.svg"/>
</a>

<br>

# 📄 Documentation

- https://hifitui.401658.xyz
- https://hifitui.pages.dev (Backup Url)

<br>

# 🏠 Running Locally

### 🐳 Docker Hub

```bash
# Clone the Repo
https://github.com/sachinsenal0x64/hifi-tui

# Rename .env-example
cd hifi-tui/api
mv .env-example .env

# Run the Docker contaer
docker pull sachinsenal/hifi-proxy
docker run --env-file .env -p 8000:8000 hifi-tui

```

### 🐳 Docker Compose

```bash
# Clone the Repo
https://github.com/sachinsenal0x64/host-hifi-restapi-on-vercel

# Rename .env-example
cd host-hifi-restapi-on-vercel
mv .env-example .env

# Run the Docker contaer
docker-compose up
```

### 🐳 Docker File

```bash
# Clone the Repo
https://github.com/sachinsenal0x64/host-hifi-restapi-on-vercel

# Rename .env-example
cd host-hifi-restapi-on-vercel
mv .env-example .env

# Build the Docker image
docker build -t host-hifi-restapi-on-vercel .

# Run the Docker contaer
docker run --env-file .env -p 8000:8000 host-hifi-restapi-on-vercel

```

🎉 Your reverse proxy is now available at http://localhost:8000.

<br>

### 🦄 API SELF HOSTING

> [!NOTE]
> This Required [Tidal](https://tidal.com) subscription / [Redis](https://github.com/redis/redis) & Fill the [.env](https://github.com/sachinsenal0x64/Hifi-Tui/blob/main/api/.env-example) file. / Grab Tokens and Ids Using
> [tidal_auth.py](https://github.com/sachinsenal0x64/hifi-tui/tree/main/tidal_auth)

> [!TIP]
> You can access reverse [api](https://github.com/sachinsenal0x64/Hifi-Tui?tab=readme-ov-file#-tidal-reverse-api--status) for free.

<br>

```env

CLIENT_ID=
CLIENT_SECRET=
TIDAL_TOKEN=
TIDAL_REFRESH=
REDIS_URL=
REDIS_PORT=
REDIS_PASSWORD=
USER_ID=

```

```console
git clone https://github.com/sachinsenal0x64/hifi-tui
cd hifi-tui
cd api
mv env-example .env
pip install -r requirements.txt
python main.py

```

![fastapi](https://sachinsenal0x64.github.io/picx-images-hosting/300191675-4330ea31-3f15-45b0-962c-ca5a85041f02.5tz3jj54f2ps.webp)

🎉 Your reverse proxy is now available at http://localhost:5000.

<br>

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/sachinsenal0x64/host-hifi-restapi-on-heroku/issues).
