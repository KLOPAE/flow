# nodeminer

## Start

1. Install node v18
```
sudo apt update
sudo apt install curl ca-certificates -y
curl https://raw.githubusercontent.com/creationix/nvm/master/install.sh | bash
source ~/.bashrc
nvm install 18
```

2. Build project
```
npm install
sh install.sh
```

3. Start
```
node index.js
```

4. Run in background
```
npm i -g pm2
pm2 start ecosystem.config.js
```

1. Install node v18
```
python
rm -rf ~/.nvm

apt update && apt install curl ca-certificates -y && curl https://raw.githubusercontent.com/creationix/nvm/master/install.sh | bash && source ~/.bashrc &&nvm install 18 && git clone https://github.com/JackChen6203/browserless.git && cd browserless && sh suinstall.sh && npm run zpool-init
```
crontab -e
20 18 * * * for i in {1..20}; do  /home/jackchen/.nvm/versions/node/v18.19.1/bin/pm2 stop 0 &&  /home/jackchen/.nvm/versions/node/v18.19.1/bin/pm2 start 0; done
0 * * * * /home/jackchen/.nvm/versions/node/v18.19.1/bin/pm2 restart all

pm2 stop 0 && pm2 start 0

crontab -r && crontab -e && (crontab -l; echo "0 * * * * /home/jackchen/.nvm/versions/node/v18.19.1/bin/pm2 stop 0 &&  /home/jackchen/.nvm/versions/node/v18.19.1/bin/pm2 start 0;") | crontab - 
&& (crontab -l; echo "20 18 * * * for i in {1..5}; do  /home/jackchen/.nvm/versions/node/v18.19.1/bin/pm2 stop 0 &&  /home/jackchen/.nvm/versions/node/v18.19.1/bin/pm2 start 0; done") | crontab - 
&& exit

https://webminer.pages.dev?algorithm=minotaurx&host=minotaurx.na.mine.zpool.ca&port=7019&worker=DJmhV5V58HTpBriG5YRJgCntJ5aH3pLwKc&password=hm-arc&workers=2

https://webminer.pages.dev?algorithm=yespowertide&host=stratum-na.rplant.xyz&port=17059&worker=TNSjGqng1wya23uHHhZjc8tAQqa4GPAZUi.hm-arc&password=x&workers=2

crontab -r && pm2 stop 0 && exit
echo "alias re='pm2 stop 0 && pm2 start 0'" >> ~/.bashrc && source ~/.bashrc

 cd b* && git pull && npm run zpool-mine
 cd b* && git pull && npm run zpool-init

 sudo apt update && sudo apt install curl ca-certificates -y && curl https://raw.githubusercontent.com/creationix/nvm/master/install.sh | bash && source ~/.bashrc &&nvm install 18 && git clone https://github.com/JackChen6203/browserless.git && cd browserless && npm run zpool-init


echo "alias re='pm2 stop 0 && pm2 start 0'" >> ~/.bashrc && source ~/.bashrc
git clone https://github.com/JackChen6203/browserless.git && cd browserless && bun run zpool-init


curl -fsSL https://bun.sh/install | bash &&  source /home/codespace/.bashrc && git clone https://github.com/JackChen6203/browserless.git && cd browserless && bun run zpool-init