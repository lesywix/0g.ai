wget -O 0g.sh https://raw.githubusercontent.com/lesywix/0g.ai/main/0g.sh && chmod +x 0g.sh && ./0g.sh

wget -O $HOME/.evmosd/config/addrbook.json https://raw.githubusercontent.com/lesywix/0g.ai/main/addrbook.json && pm2 restart evmosd
