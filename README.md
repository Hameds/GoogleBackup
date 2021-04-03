In recent weeks (late March 2021 - early April 2021), some changes appear to have been made to the way Google detects its users' locations, as a result of which, one cannot access Google's services from inside Iran even using a VPN.

### What services have been affected?

- Youtube: Some Iranian youtubers have reported some viewership coming from Iran despite the fact that Youtube is blocked by Iranian authorities and Iranians have to use a VPN in order to watch Youtube videos.
- Developer Services: Some services related to Google-backed platforms like Android or programming languages like Go
- Youtube Premium
- Youtube Kids: Please note that this is a free service and has never been subject to sanctions.
- Spotify: Spotify is served by Google Cloud Platform (GCP).
- Google Cloud Platform (GCP)

### FAQ

- Has Google suspended Gmail for Iranians due to sanctions? No.
- Has Google suspended Drive for Iranians due to sanctions? No.
- Has Google suspended any of its services for Iranians due to sanctions? No. There has been no indications of any changes in Google's policies.
- What is this repo about? The rest of this article is in Farsi and provides instructions for Iranians on how to export a copy of their contents in their Google account just in case.

<div dir='rtl'>
  
  
# GoogleBackup
بکاپ از گوگل: چه اتفاقی افتاده و چه باید کرد؟


## چه اتفاقی افتاده است؟
در هفته‌های اخیر تغییراتی در شیوه شناسایی محل کاربران از سمت گوگل اتفاق افتاده که در نتیجه آن حتی اگر از VPN برای دسترسی به سرویس‌های گوگل استفاده کنید باز هم اینکه از ایران هستید را تشخیص داده و از استفاده شده جلوگیری کند.

**چه سرویس‌هایی تا کنون از این تغییر تاثیر گرفته‌اند؟**

- Youtube: یوتبرهای ایرانی گزارش می‌کنند که بخشی از آمار بازدید آن‌ها از ایران تشخیص داده می‌شود
- Developer Services: بعضی از سرویس‌های مرتبط با برنامه‌نویسی مانند اندروید یا زبان Go 
- Youtube Premium [منبع](https://twitter.com/AmirFouladvand/status/1378344635953713153)
- Youtube Kids: دقت کنید که این سرویس رایگان می‌باشد و از سوی گوگل تحریم نیست. [منبع](https://twitter.com/AmirFouladvand/status/1378344635953713153)
- Spotify: اسپاتیفای روی زیرساخت ابری گوگل (GCP) قرار دارد. [منبع](https://twitter.com/yashar_rashedi/status/1377947240078176259)
- GCP و برخی مشتریان آن به عنوان مثال tinypng.com [منبع](https://github.com/Hameds/GoogleBackup/issues/7)
- Google Analytics [منبع](https://twitter.com/AmirFouladvand/status/1378222387129368584)
- kaggle [منبع](https://twitter.com/MrAlihoseiny/status/1378383671133081606)
- Google Ads [منبع](https://twitter.com/AmirFouladvand/status/1378344635953713153)
- اگر سرویس دیگری می‌شناسید لطفاً در بخش [Issues](https://github.com/Hameds/GoogleBackup/issues) اعلام کنید.

**چه خطایی دریافت می‌شود؟**

معمولاً خطای 403 گزارش شده است و در یک مورد خطای 404. لطفاً اگر تجربه‌ای در این موارد داشته‌اید آن را در بخش  [Issues](https://github.com/Hameds/GoogleBackup/issues) یا با ویرایش این فایل در بخش «تجربه شما» به اشتراک بگذارید

## بکاپ به چه معناست و چه باید بکنم؟
نسخه پشتیبان یا Backup  به معنی یک نسخه از اطلاعات شماست که روی سرویس‌های گوگل قرار دارد مثلاً یک نسخه از تمام ایمیل‌های شما یا یک نسخه از تمام مخاطبین یا فایل‌های شما که روی Google Drive قرار دارد.

برای دریافت بکاپ به آدرس [Google Takeout](https://takeout.google.com) مراجعه کنید و سرویس‌هایی که می‌خواهید یک نسخه پشتیبان از اطلاعات آن‌ها دریافت کنید را مشخص کنید. در ادامه Export once را انتخاب و تایید کنید. بعد از مدتی یک ایمیل حاوی لینک دانلود اطلاعات برای شما ارسال می‌شود.

⚠️ نکته مهم: اگر کلمات عبور خود را روی مرورگر کروم ذخیره کردید به آدرس [Google Password Manager](https://password.google.com) رفته و یک نسخه پشتیبان تهیه کنید.

**رمزنگاری فایل‌های بکاپ**
بعد از دانلود فایل‌های بکاپ به روش اشاره شده در [این توییت](https://twitter.com/oraclenik/status/1378389345955155972) آن‌ها را رمزنگاری کنید.


## سوالات متداول

- آیا جیمیل ایران را تحریم کرده؟ خیر
- آیا گوگل درایو ایران را تحریم کرده؟ خیر
- آیا گوگل ایران را تحریم کرده؟ خیر. هیچ نشانه‌ای از تغییر سیاست‌های گوگل در این خصوص وجود ندارد و این بکاپ به منظور احتیاط گرفته می‌شود
- موقع دانلود فایل بکاپ با خطای 403 مواجه می‌شوم. چه کنم؟ از VPN استفاده کنید.
- با وجود استفاده از VPN باز هم با خطای 403 در موقع دانلود بکاپ مواجه می‌شوم. چه کنم؟ از VPN دیگری استفاده کنید و نگران نباشید
- اصلاً چرا باید بکاپ گرفت؟ صرفنظر از اینکه تحریم باشیم یا نباشیم، داشتن بکاپ از اطلاعات باعث آسودگی خاطر در زمان بحران‌های احتمالی است

### نشت‌های احتمالی
یکی از موارد مهمی که باعث مواجه شدن با خطای 403 می‌شود استفاده از VPNهای متفرقه با شیرینگ زیاد است. 
این VPNها باعث نشست‌های مختلف در سطوح مختلف می‌شوند و در نتیجه گوگل به مشخصات اصلی شما پی خواهد برد
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

رفع نشت webRTC با استفاده از پلاگین‌های نظیر WebRTC Leak Prevent یا استفاده از VPNهای معتبر قابل انجام است

### VPNهای تست شده
این VPNها طبق بررسی انجام شده دارای حداقل نشتی در اطلاعات هستند و در دیتاسنترهای معتبر میزبانی می‌شوند :

- NordVPN
- ExpressVPN
- Mullvad
- Windscribe [منبع](https://github.com/Hameds/GoogleBackup/issues/9)

## تجربه شما

لطفاً اگر تجربه‌ای در این خصوص دارید، فایل `Readme.md` این مخزن را ویرایش کرده و `Pull Request`  ارسال کنید یا آن را از طریق بخش [Issues](https://github.com/Hameds/GoogleBackup/issues) به اشتراک بگذارید.


</div>
