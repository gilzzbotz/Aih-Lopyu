

- 👋 Hi, I’m @Arifxyzzz
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Arifxyzzz/Arifxyzzz is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
## Buildpack 
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Arifxyzzz/Rifbotz)
| BuildPack | LINK |

|--------|--------|

| **FFMPEG** |[here](https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest) |

| **IMAGEMAGICK** | [here](https://github.com/DuckyTeam/heroku-buildpack-imagemagick) |

---------

## HOW TO CONNECT TO MONGODB WHEN RUN IN HEROKU

* Create account and database in mongodb atlas [`watch here`](https://youtu.be/rPqRyYJmx2g)

* when you already have a database, you just need to take mongourl

* Put mongourl in Procfile `web: node . --db 'mongourl'`

* Example `web: node . -- db 'Your Mongo URI'`

---------

## FOR TERMUX/UBUNTU/SSH USER

```bash

apt update && apt upgrade

apt install git -y

apt install nodejs -y

apt install ffmpeg -y

apt install imagemagick -y

git clone https://github.com/Aiinne/Aine-MD

cd Aine-MD

pkg install yarn

yarn
