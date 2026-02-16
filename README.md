<h1>Yeni Nesil Tamamen Türkçe Müzik Botu</h1>

Telegram sohbet gruplarında hem müzik dinleyebileceğiniz hem de video izleyebileceğiniz müzik botudur.
Bot tamamen açık kaynak kodludur istediğiniz gibi kullanabilirsiniz.

## DEVELOPER İLETİŞİM
<b>Telegram:</b> <a href="https://t.me/ToxicTR">Toxic</a> ulaşabilirsiniz. <br>

## 🖇 VPS Deployment
<code>
git clone https://github.com/ToxicTR/Toxic-Music
cd Toxic-Music
sudo apt-get update && sudo apt-get upgrade -y
sudo apt-get install python3-pip ffmpeg -y
sudo pip3 install -U pip
curl -fssL https://deb.nodesource.com/setup_17.x | sudo -E bash - && sudo apt-get install nodejs -y && npm i -g npm #bunu yapmadan önce node.js kurulumu yapın
pip3 install -U -r requirements.txt
cp sample.env .env
nano .env
</code>

## nodejs kurulumu sürüm düşük hatası alıyorsanız aşağıdaki komutları uygulayın.
<code>
 sudo apt install nodejs
 sudo apt install npm
 sudo npm cache clean -f
 sudo npm install -g n
 sudo n stable
</code>

## .env dosyasını VDS'te iken aşağıdaki değerleri kopyalayın ve yapıştırın.

<code>
API_ID= my.telegram.org adresinden alacaksiniz
API_HASH= my.telegram.org adresinden alacaksiniz
BOT_TOKEN= Bot tokeninizi telegramdan @BotFather dan alabilirsiniz
MONGO_DB_URI= https://www.mongodb.com/ adresinden alacaksiniz.
LOG_GROUP_ID= sohbet grubu id'si @raw_data_bot tan öğrenebilirsiniz
MUSIC_BOT_NAME= müzik botunuzun adi
STRING_SESSION= asistan hesabinin string session almaniz için https://replit.com/@AssadAli/String-Session-Generator
SPOTIFY_CLIENT_ID = developer.spotify.com adresinden alacaksiniz
SPOTIFY_CLIENT_SECRET = developer.spotify.com adresinden alacaksiniz
OWNER_ID = sahip(sizin) kullanici kimliğiniz bunu userinfobot tan ya da herhangi bir gruptan info çekerek öğrenebilirsiniz.

UPSTREAM_REPO = https://github.com/ToxicTR/Toxic-Music
UPSTREAM_BRAMCH = master
PRIVATE_BOT_MODE = False
YOUTUBE_EDIT_SLEEP = 3
TELEGRAM_EDIT_SLEEP = 5
AUTO_LEAVING_ASSISTANT = false
ASSISTANT_LEAVE_TIME = 5400
</code>

Nanoda <code>Ctrl+X</code> yaparak hepsine <code>yes</code> yaparak kayıt edip çıkın.

## Botu başlatmadan önce yapmaniz gerekenler
<code>
screen -S "botunuzunAdi"
chmod 777 *
</code>

## Bunları yaptıktan sonra;

<code>screen bash start</code> ya da <code>screen ./start</code> yapın.

Botunuz aktif olacaktır.

## Keyifli dinlemeler 

## DİKKAT!

Botunuzu ve asistaninizi açtığınız log grubunda tam yetki vermezseniz ve sesli sohbeti açık bırakmazsanız çalışmaz!

.
