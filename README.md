# crochess
live: http://bit.ly/3l475me

![screenshot of active game](https://i.postimg.cc/26nMHfwr/Screenshot-from-2022-05-22-16-45-03.png)

![screenshot of home page](https://i.postimg.cc/GhjsvD7h/Screenshot-from-2022-05-13-12-55-15.png)

croChess is a free online chess game server that lets you play against your friends in realtime. 

[croChess-backend](https://github.com/lookingcoolonavespa/crochess-backend/tree/18344525d0778a29f6c8a200a9ac0f85efbdaf1f) is written in Typescript, runs in [Node.js](https://nodejs.org/en/), and relies on the [Express](https://expressjs.com/) framework.

The [frontend](https://github.com/lookingcoolonavespa/crochess-frontend/tree/58f9ddc38e4c35018fbbc0752b534e0f1863cde4) is writtein in Typescript, runs on [Next.js](https://nextjs.org/), and uses Sass to generate Css. 

Pure chess logic is contained in the [croChess-api](https://github.com/lookingcoolonavespa/crochess-api) submodule.

All games are stored on [MongoDB](https://www.mongodb.com/). 

Checkout the docs: 
- [chess logic](https://github.com/lookingcoolonavespa/crochess-api/blob/main/README.md)
- [backend](https://github.com/lookingcoolonavespa/crochess-backend)
