Welcome to my GitHub profile!

Most of my coding hours are spent at work, but I have a couple of personal projects that I work on from time to time. These projects sometimes end up here.

My latest project is `Sky-Write`, a note-taking web application. I started this project after having a very poor experience with Microsoft's OneNote app for Android. Please feel free to try it out! The web app has been deployed here: https://sky-write.app

Thank you for visiting!

<!---
If you would like to try `SkyWrite`, you can visit its back-end and UI repos from this page, or you can run this script to try it immediately (requires Docker and Yarn, at least):

```sh
mkdir sky_write_example
cd sky_write_example
git clone https://github.com/davidhammaker/SkyWriteBE.git
git clone https://github.com/davidhammaker/SkyWriteUI.git
cd SkyWriteBE
printf "
export SECRET=InsecureSecretForExample
export RELOAD=--reload
export DEBUG=1
export DEV=1
export DJANGO_SETTINGS_MODULE=sky_write_django.settings
" > .env
## Ubuntu users:
# sudo chown -R $USER:$USER .
docker-compose up -d --build
docker exec -it skywritebe_web_1 python3 manage.py makemigrations
docker exec -it skywritebe_web_1 python3 manage.py migrate
cd ../SkyWriteUI
yarn install
yarn start
```

- If any part of this script gives you an error, please let me know! My email address is on this profile.
--->
<!---
- 👋 Hi, I’m @davidhammaker
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
--->

<!---
davidhammaker/davidhammaker is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
