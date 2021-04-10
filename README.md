# Google Backup

In recent weeks (late March 2021 - early April 2021), some changes appear to have been made to the way Google detects its users' locations, as a result of which, one cannot access Google's services from inside Iran even using a VPN.

### What services have been affected?

- Youtube: Some Iranian youtubers have reported some viewership coming from Iran despite the fact that Youtube is blocked by Iranian authorities and Iranians have to use a VPN in order to watch Youtube videos.
- Developer Services: Some services related to Google-backed platforms like Android or programming languages like Go
- Youtube Premium
- Youtube Kids: Please note that this is a free service and has never been subject to sanctions.
- Spotify: Spotify is served by Google Cloud Platform (GCP).
- Google Cloud Platform (GCP)
- Google Analytics
- kaggle
- Google 2FA
- Google OAuth 2.0
- Google Prompt
- Firebase Remote Config
- Firebase Auth
- Google Workspace
- Google Play Books
- Google Ads
- Google Play Console
- Castbox
- Google Scholar
- Google Podcasts
- Google Container Registry
- Last.fm
- Waze 
- Google Family
- Slite (slite.com)
- Google One
- Toggl
- Grafana.com
- Firebase Dynamic Links
- Youtube Music

### FAQ

- Has Google suspended Gmail for Iranians due to sanctions? No.
- Has Google suspended Drive for Iranians due to sanctions? No.
- Has Google suspended any of its services for Iranians due to sanctions? No. There has been no indications of any changes in Google's policies.
- What is this repo about? The rest of this article is in Farsi and provides instructions for Iranians on how to export a copy of their contents in their Google account just in case.

<div dir='rtl'>
  

## چه اتفاقی افتاده است؟
در هفته‌های اخیر تغییراتی در شیوه شناسایی محل کاربران از سمت گوگل اتفاق افتاده که در نتیجه آن حتی اگر از VPN برای دسترسی به سرویس‌های گوگل استفاده کنید باز هم اینکه از ایران هستید را تشخیص داده و از استفاده از بعضی سرویس‌ها جلوگیری کند. بعضی این را مرتبط با [تغییرات در مالیات از درآمد یوتوب](https://support.google.com/youtube/answer/10391362?hl=en) می‌دانند که باعث شده گوگل مکانیزم شناسایی محل کاربران را بروز کند.

**چه سرویس‌هایی تا کنون از این تغییر تاثیر گرفته‌اند؟**

- Youtube: یوتبرهای ایرانی گزارش می‌کنند که بخشی از آمار بازدید آن‌ها از ایران تشخیص داده می‌شود. [منبع](https://twitter.com/amirabbas/status/1377186765358854144)
- Developer Services: بعضی از سرویس‌های مرتبط با برنامه‌نویسی مانند بخش توسعه‌دهندگان اندروید [منبع](https://twitter.com/ErFUN_KH/status/1378320906213339136) یا زبان Go [منبع](https://twitter.com/ans_ashkan/status/1378370073765756928) 
- Youtube Premium [منبع](https://twitter.com/AmirFouladvand/status/1378344635953713153)
- Youtube Kids: دقت کنید که این سرویس رایگان می‌باشد و از سوی گوگل تحریم نیست. [منبع](https://twitter.com/AmirFouladvand/status/1378344635953713153)
- Spotify: اسپاتیفای روی زیرساخت ابری گوگل (GCP) قرار دارد. [منبع](https://twitter.com/yashar_rashedi/status/1377947240078176259)
- GCP و برخی مشتریان آن به عنوان مثال tinypng.com و ifconfig.me [منبع](https://github.com/Hameds/GoogleBackup/issues/7)
- Google Analytics [منبع](https://twitter.com/AmirFouladvand/status/1378222387129368584)
- kaggle [منبع](https://twitter.com/MrAlihoseiny/status/1378383671133081606)
- Google 2FA [منبع](https://twitter.com/only_sadeghi/status/1378437673162043392)
- Google OAuth 2.0 [منبع](https://twitter.com/babakmhz/status/1378364207482212358)
- Google Prompt [منبع](https://github.com/Hameds/GoogleBackup/issues/13)
- Firebase Remote Config [منبع](https://twitter.com/behdad222/status/1378688158494289922) با این مورد عملاً اپ‌هایی که از این قابلیت استفاده می‌کنند امکان بروزرسانی راه‌دور تنظیمات نیست و برای کاربران بسیاری مشکل ایجاد خواهد کرد. این مساله حتی با VPN هم حل نمی‌شود
- Firebase Auth: این سرویس قبلاً هم برای این تحریم بوده اما به کمک VPN می‌شده در اپ‌هایی که از این قابلیت استفاده کردند حساب کاربری ساخت یا وارد شد اما حالا حتی با VPN هم نمی‌شود این کار را کرد. اپ‌های زیادی از این قابلیت استفاده می‌کنند و این مساله برای کاربران مشکل ایجاد خواهد کرد.
- Google Workspace [منبع](https://twitter.com/MesgariSaber/status/1378745573042487302)
- Google Play Books [منبع](https://twitter.com/MesgariSaber/status/1378746603759144961)
- Google Ads [منبع](https://twitter.com/alirezaord/status/1378417030500642823)
- Google Play Console [منبع](https://twitter.com/MrOplus/status/1378780969637920776)
- Castbox [منبع](https://twitter.com/AmirFouladvand/status/1379023024494678017)
- Google Scholar [منبع](https://twitter.com/mohammadfrji/status/1379006969223208961)
- Google Podcasts [منبع](https://github.com/Hameds/GoogleBackup/issues/31)
- Google Container Registry [منبع](https://github.com/Hameds/GoogleBackup/issues/28)
- Last.fm [منبع](https://twitter.com/don_wp/status/1378256122071687168)
- Waze [منبع](https://github.com/Hameds/GoogleBackup/issues/27) در مورد این مسیریاب، کاربران دیگری هم به بروز خطا اشاره داشته‌اند
- Google Family [منبع](https://github.com/Hameds/GoogleBackup/issues/27)
- Slite [منبع](https://twitter.com/MesgariSaber/status/1378780262537048066)
- Google One [منبع](https://github.com/Hameds/GoogleBackup/issues/41)
- Toggl [منبع](https://github.com/Hameds/GoogleBackup/issues/40)
- Grafana.com [منبع](https://github.com/Hameds/GoogleBackup/issues/37)
- Firebase Dynamic Links [منبع](https://github.com/Hameds/GoogleBackup/issues/45)
- Youtube Music [منبع](https://github.com/Hameds/GoogleBackup/issues/44)
- اگر سرویس دیگری می‌شناسید لطفاً در بخش [Issues](https://github.com/Hameds/GoogleBackup/issues) اعلام کنید.

**چه خطایی دریافت می‌شود؟**

معمولاً خطای 403 گزارش شده است و در یک مورد خطای 404 [منبع](https://twitter.com/bkhezry/status/1377970749374365697). لطفاً اگر تجربه‌ای در این موارد داشته‌اید آن را در بخش  [Issues](https://github.com/Hameds/GoogleBackup/issues) یا با ویرایش این فایل در بخش «تجربه شما» به اشتراک بگذارید

## بکاپ به چه معناست و چه باید بکنم؟
نسخه پشتیبان یا Backup  به معنی یک نسخه از اطلاعات شماست که روی سرویس‌های گوگل قرار دارد مثلاً یک نسخه از تمام ایمیل‌های شما یا یک نسخه از تمام مخاطبین یا فایل‌های شما که روی Google Drive قرار دارد.

برای دریافت بکاپ به آدرس [Google Takeout](https://takeout.google.com) مراجعه کنید و سرویس‌هایی که می‌خواهید یک نسخه پشتیبان از اطلاعات آن‌ها دریافت کنید را مشخص کنید. در ادامه Export once را انتخاب و تایید کنید. بعد از مدتی یک ایمیل حاوی لینک دانلود اطلاعات برای شما ارسال می‌شود.

⚠️ نکته مهم: اگر کلمات عبور خود را روی مرورگر کروم ذخیره کردید به آدرس [Google Password Manager](https://passwords.google.com) رفته و یک نسخه پشتیبان تهیه کنید.

**رمزنگاری فایل‌های بکاپ**

بعد از دانلود فایل‌های بکاپ به روش اشاره شده در [این توییت](https://twitter.com/oraclenik/status/1378389345955155972) آن‌ها را رمزنگاری کنید.

**خطای 403 زمان دانلود بکاپ**
در بخش سوالات متداول توضیح داده شده که اگر خطای 403 دریافت کردید از VPN استفاده کنید. اما توجه داشته باشید که اگر چندین بار اقدام به دانلود کنید و خطا دریافت کنید 
برای دانلود دچار مشکل خواهید شد

![DownloadError](https://user-images.githubusercontent.com/47300215/113522101-4688ff00-95b3-11eb-98a8-94a74c4a33a4.png)

در این شرایط مطابق توضیحی که در بخش سوالات متداول داده شده از One Drive مایکروسافت کمک بگیرید

## سوالات متداول

- آیا جیمیل ایران را تحریم کرده؟ خیر
- آیا گوگل درایو ایران را تحریم کرده؟ خیر
- آیا گوگل ایران را تحریم کرده؟ خیر. هیچ نشانه‌ای از تغییر سیاست‌های گوگل در این خصوص وجود ندارد و این بکاپ به منظور احتیاط گرفته می‌شود
- بعد از اقدام به بکاپ، به من می‌گوید چند ساعت یا چند روز طول می‌کشد بکاپ آماده شود. چه کنم؟ نگران نباشید، خیلی زود لینک دانلود بکاپ ایمیل خواهد شد.
- موقع دانلود فایل بکاپ با خطای 403 مواجه می‌شوم. چه کنم؟ از VPN استفاده کنید.
- با وجود استفاده از VPN باز هم با خطای 403 در موقع دانلود بکاپ مواجه می‌شوم. چه کنم؟ از VPN دیگری استفاده کنید و نگران نباشید
- با هیچ VPN نتوانستم فایل بکاپ را دانلود کنم. چه کنم؟ طبق راهنمایی [این توییت برای استفاده از OneDrive](https://twitter.com/hamidziaei/status/1378586883878440962) عمل کنید
- اصلاً چرا باید بکاپ گرفت؟ صرفنظر از اینکه تحریم باشیم یا نباشیم، داشتن بکاپ از اطلاعات باعث آسودگی خاطر در زمان بحران‌های احتمالی است
- برنامه‌نویس هستم و برای دسترسی به سرویس‌ها مشکل دارم. چه کنم؟ اگر اکانت شما غیرفعال نشده ظاهراً در حال حاضر از [fodve.org](http://fodev.org) برای دسترسی داشتن می‌تونید استفاده کنید.

## نشت‌های احتمالی
یکی از موارد مهمی که باعث مواجه شدن با خطای 403 می‌شود استفاده از VPNهای متفرقه با شیرینگ زیاد است. 
این VPNها باعث نشت‌های مختلف در سطوح مختلف می‌شوند و در نتیجه گوگل به مشخصات اصلی شما پی خواهد برد
#### برخی از این نشت‌ها (leaks)
##### IP and DNS leaks
این نشت زمانی اتفاق می‌افتد که VPN شما تنها برای گذر از فیلترینگ طراحی شده و توانایی رمزنگاری دیتا در سطح بالا را ندارد به همین دلیل آی‌پی اصلی شما مشخص خواهد شد

**تست و بررسی این نشست:**
https://browserleaks.com/ip

در صورتی که در بخش DNS Leak Test آی‌پی به غیر از آی‌پی VPN مشاهده می‌کنید به معنای مثبت بودن نشستی است

##### WebRTC leak:
نشست webRTC یکی از دیگر نشست‌هایی است که در سطح مرورگر باعث دسترسی به اطلاعات شما می‌شود و علیرغم استفاده از VPN با خطای 403 مواجه خواهید شد

برای بررسی این نشست نیز می‌توانید از سایت‌های زیر استفاده کنید:

- https://ip.voidsec.com/
- https://browserleaks.com/webrtc

رفع نشت webRTC با استفاده از پلاگین‌های نظیر WebRTC Leak Prevent یا استفاده از VPNهای معتبر قابل انجام است. <br />
برای رفع webRTC Leak در فایرفاکس در نوار آدرس about:config رو نوشته و واردش شوید، سپس روی دکمه Accept the Risk and Continue کلیک کرده، سپس media.peerconnection.enabled و media.navigator.enabled سرچ کرده و با دوبار کلیک کردن برروی آن مقدار آنرا False قرار دهید.

##### Timezone:
یکی از راه های شناخت کشور کاربر، دریافت منطقه زمانی از مرورگر هست

برای بررسی این نشست نیز می‌توانید از سایت‌های زیر استفاده کنید:

https://webbrowsertools.com/timezone/

افزونه هایی مثل Spoof Timezone می تونن منطقه زمانی شما به منطقه زمانی VPN ای که دارید تغییر بدن

https://chrome.google.com/webstore/detail/spoof-timezone/kcabmhnajflfolhelachlflngdbfhboe?hl=en

### VPNهای تست شده
این VPNها طبق بررسی انجام شده دارای حداقل نشتی در اطلاعات هستند و در دیتاسنترهای معتبر میزبانی می‌شوند :

- NordVPN
- ExpressVPN
- Mullvad
- Windscribe [منبع](https://github.com/Hameds/GoogleBackup/issues/9)
- Keepsolid (Redeem a code : VPNMACXDNS | 6 months free)

## محتویات فایل‌ بک‌آپ
فایل بک‌آپ شامل تمام داده‌های سرویس‌های مختلف گوگل میباشد. مثلا:

- عکس‌هایی که توی گوگل‌فوتوز آپلود کردید +‌ فایل‌های متادیتاشون
- تمام ایمیل‌هاتون با فرمت Mbox موجوده که میتونید توی کلاینت‌های استاندارد ایمیل مشاهده کنیدشون
- کانال‌هایی که توی یوتیوب دنبال کردید یا پلی لیست‌ها یا حتی ویدیو‌هایی که لایک کردید و ... همگی به صورت json وجود داره
- تمام فایل‌های گوگل درایو
- لیست کانتکت‌هاتون با فرمت VCF
- چت‌های hangout و فایل‌هاش
- و ...

![Capture](https://user-images.githubusercontent.com/21690865/113487292-7d381a00-94cc-11eb-8db3-0747bd822b29.PNG)

<sub>تصویر پوشه‌های داخل فایل بک‌آپ</sub>

## تجربه شما

لطفاً اگر تجربه‌ای در این خصوص دارید، فایل `Readme.md` این مخزن را ویرایش کرده و `Pull Request`  ارسال کنید یا آن را از طریق بخش [Issues](https://github.com/Hameds/GoogleBackup/issues) به اشتراک بگذارید.


</div>
