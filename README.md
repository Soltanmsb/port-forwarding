# port-forwarding
TyPe &lt;/> HaCk

پورت فرواردینگ با سایت localhost.run:

ابتدا در ترموکس به پوشه یا محلی که سورس سایت یا ابزار مورد نظرتون هست برید،
سپس اونجا این دستور رو بزنید :

<br><pre>pkg install php</pre>

<br><pre>php -S 127.0.0.1:3333</pre>

تا لوکال هاست اجرا بشه، ( به جای 3333 میتونید پورت دلخواه خودتون رو بنویسید مثلا 8888 یا .. )
حالا اگه درون مرورگر بنویسید <br><pre>http://127.0.0.1:3333</pre>
براتون کدتونو اجرا می کنه ولی فقط برای خودتونه 🙂
سپس یه صفحه جدید باز کنید و داخلش کد زیر رو بزنید: 

<br><pre>ssh -R 80:127.0.0.1:3000 nokey@localhost.run</pre>

<img src="https://soltanmsb.vhbot.xyz/personal%20files/IMG_20220407_143408_293.jpg">



<h1><a href="https://soltanmsb.vhbot.xyz/personal%20files/InShot_%DB%B2%DB%B0%DB%B2%DB%B2%DB%B0%DB%B4%DB%B0%DB%B7_%DB%B1%DB%B5%DB%B1%DB%B3%DB%B5%DB%B0%DB%B1%DB%B0%DB%B1.mp4">فیلم آموزشی</h1>

<h2><a href="https://t.me/hacking_01">کانال ما</h2>

<h2><a href="https://t.me/hacking_01_bot">ربات ما</h2>


