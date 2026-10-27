[RELEASE-NOTES-v1.2.0.md](https://github.com/user-attachments/files/34015237/RELEASE-NOTES-v1.2.0.md)
# GoLAN v1.2.0

> 🆕 **اسم برنامه عوض شد: Virtual LAN Platform ← GoLAN.** با لوگوی تازه، ظاهر کاملاً نو و عکس پروفایل. شبکه و پروتکل دست نخورده‌ان، پس ۱.۲.۰ و ۱.۱.۰ هنوز به هم وصل می‌شن. فقط برای دیدن عکس پروفایل بقیه، **میزبان اتاق** هم باید ۱.۲.۰ باشه.

این به‌روزرسانی روی چیزیه که جلوی چشمته: برنامه از نو طراحی شده، عکس پروفایل اومده، و مشکل ارقام فارسی و نقطه‌ها که با زبان ویندوز خراب می‌شد از ریشه درست شده.

---

## 🎨 طراحی جدید

- **اسم و لوگوی تازه:** GoLAN. لوگو روی نوار بالا، تسکبار، نصب‌کننده و آیکون برنامه عوض شده.
- **تم تیره‌ی سیاه‌تر.** پس‌زمینه تقریباً مشکیه و رنگ‌ها از نو تنظیم شدن؛ تم روشن هم همراهش به‌روز شده.
- **همه‌ی صفحه‌ها از نو ساخته شدن:** لابی، اتاق، تنظیمات (پنج بخش)، پیش‌بررسی شبکه، راهنمای UPnP، «چی جدیده؟»، مودال‌ها، توست‌ها و صفحه‌ی بستن.
- **IP میزبان و IP خودت** هر دو بالای اتاق هستن و با یک کلیک کپی می‌شن — برای وقتی که بازی یا دوستت IP‌ت رو می‌خواد.
- **فونت‌ها داخل خود برنامه‌ان:** Inter برای متن لاتین، Vazirmatn برای فارسی و JetBrains Mono برای IP و کدها. روی هر سیستمی، با هر زبان ویندوزی، یک‌شکل دیده می‌شه.
- **انیمیشن‌های نرم‌تر:** پنجره‌ها و صفحه‌های تنظیمات با محو شدن و بالا اومدن کوچیک باز می‌شن، دکمه‌ها موقع کلیک کمی فرو می‌رن و روشن شدنشون نرمه، و ردیف اعضا زیر ماوس برجسته می‌شه.
- **دیگه خط‌چینی دور دکمه‌ها نمیاد** (مثلاً دکمه‌ی «Keep running» موقع بستن). فوکوس کیبورد هنوز با یک حاشیه‌ی آبی دیده می‌شه.

---

## 🖼 عکس پروفایل

از **تنظیمات ← عمومی ← عکس پروفایل**.

- **قبل از ذخیره می‌تونی کراپ و زوم کنی.** عکس رو توی یه پنجره‌ی گرد می‌کشی و با اسلایدر یا چرخ ماوس بزرگ و کوچیکش می‌کنی. عکس‌های گوشی که چرخیده ذخیره شدن هم خودکار صاف می‌شن.
- **توی لیست اعضا** کنار اسم هر نفر دیده می‌شه، با نقطه‌ی وضعیت روش.
- **توی چت مثل تلگرام:** اسم بالای اولین پیام هر پشت‌سرهم می‌مونه، و عکس کنار **آخرین** پیام اون نفر می‌شینه، همون‌جا که دُم حباب هم هست.
- کسی که عکس نذاشته، مثل قبل با حرف اول اسمش و رنگ مخصوصش دیده می‌شه.
- عکس به ۱۹۲×۱۹۲ پیکسل کوچیک می‌شه (چند ده کیلوبایت) و همون موقع که وارد اتاق می‌شی یا عوضش می‌کنی برای بقیه می‌ره. میزبان اون رو به بقیه می‌رسونه و برای کسی که تازه وارد شده همه‌ی عکس‌ها رو می‌فرسته.
- **حریم خصوصی:** عکس فقط به اعضای همون اتاق می‌رسه و موقع خروج از اتاق از حافظه‌ی بقیه پاک می‌شه. هیچ سروری نیست که ذخیره‌ش کنه.

> فقط یه نوع پیام تازه (`Avatar`) اضافه شده؛ قالب فریم و نسخه‌ی پروتکل عوض نشده. میزبانِ ۱.۱.۰ عکس رو نمی‌رسونه، پس تا میزبان به‌روز نشه، عکس‌ها دیده نمی‌شن — ولی اتصال عادی کار می‌کنه.

---

## 🔢 ارقام فارسی و فونت

دو مشکل واقعی توی ارقام بود و هر دو از ریشه درست شدن.

| قبل | بعد |
|---|---|
| با «ارقام فارسی» روشن، نقطه‌ی IP تبدیل به یک مربع می‌شد | نقطه‌ها همیشه هستن؛ IP، پورت و کدها همیشه لاتین‌ان |
| با ویندوز فارسی هم همین خرابی پیش می‌اومد | زبان و فرمت منطقه‌ای ویندوز دیگه روی ظاهر برنامه اثر نداره |
| «123 لاتین» توی تنظیمات با انتخاب فارسی، خودش فارسی می‌شد | برچسب لاتین همیشه لاتینه |
| درصد میکروفن و اسپیکر با یه فونت نامناسب | با فونت اصلی برنامه و وزن مناسب |

**چرا خراب می‌شد:** ارقام فارسی رو با تبدیل خودکار خود WPF نشون می‌دادیم، و اون تبدیل نقطه رو هم به یه نویسه‌ی فارسی می‌کرد که هیچ فونتی نداره. حالا متن همیشه ASCII می‌مونه و ارقام فارسی با یه فونت مخصوص (فقط ده رقم، بریده از Vazirmatn) کشیده می‌شن.

- **توی چت:** پیام فارسی با رقم فارسی نشون داده می‌شه (اگه تنظیمش روشن باشه)، و پیام انگلیسی مثل `connect 192.168.1.12:25565` همون‌طور که تایپ شده می‌مونه.
- اگه با کیبورد فارسی رقم بزنی (مثلاً توی کادر پورت یا درصد صدا)، خودش به رقم درست تبدیل می‌شه.

---

## 🐞 رفع باگ

- **خطای «`Paragraph` is not a Visual or Visual3D»:** کلیک روی متن یه پیام توی چت می‌تونست برنامه رو به خطا بندازه. درست شد.
- **میکروفن یا اسپیکر روی ۰٪:** به‌جای ضربدر قرمز، آیکون خاکستری می‌شه؛ قرمز فقط برای «قطع» موند.
- **خط‌چین دور دکمه‌ها** (بالا).

---

## 😀 ایموجی

ایموجی‌های داخلی همون ایموجی سه‌بعدی قبلین. اگه مجموعه‌ی دلخواهی داری که حق استفاده ازش رو داری، تصویرها رو توی `%LOCALAPPDATA%\VirtualLANPlatform\emoji` بذار (اسم فایل = کد هگز ایموجی، مثل `1f600.png`) تا جای ایموجی داخلی استفاده بشن. نیازی به نصب دوباره نیست.

---

## 📥 نصب

فایل `VirtualLANPlatform_Setup_v1.2.0.exe` رو دانلود و اجرا کن. اگه نسخه‌ی قبلی رو داری، روش نصب می‌شه و تنظیمات، اسم و عکست می‌مونن.

نیازمندی‌ها: ویندوز ۱۰ نسخه ۱۸۰۹ به بالا، ۶۴ بیتی. اگه .NET 8 Desktop Runtime نصب نباشه، خود نصب‌کننده دانلودش می‌کنه.

**تأیید فایل** (اختیاری):

```powershell
(Get-FileHash VirtualLANPlatform_Setup_v1.2.0.exe -Algorithm SHA256).Hash
```

باید این باشه:

```
9C81A0724ECBB2DCED404E664A13883E59F2DBAA330D0A4E2A2C43CE09B931D2
```

---

<details>
<summary><b>English</b></summary>

## GoLAN v1.2.0

> 🆕 **Virtual LAN Platform is now GoLAN** — new logo, a redesigned interface and profile pictures. The network layer and wire protocol are unchanged, so 1.2.0 still connects to 1.1.0. To see other people's pictures, the **room host** needs 1.2.0 as well.

### Design

A new name and logo, a near-black dark theme (with the light theme brought along), and every screen rebuilt: lobby, room, settings, network pre-check, UPnP guide, What's new, dialogs, toasts and the shutdown screen. Both the host's address and your own sit at the top of the room, one click to copy. Fonts ship inside the app — Inter, Vazirmatn and JetBrains Mono — so it looks the same on every machine. Windows and settings pages ease in, buttons sink slightly when pressed, member rows lift under the pointer. The dotted focus rectangle around buttons is gone.

### Profile pictures

Settings → General → Profile picture. Crop and zoom in a round window before saving (phone photos are turned upright automatically). The picture shows in the member list and, Telegram-style, beside the **last** bubble of each run of messages, where the bubble's tail is. It is shrunk to 192 × 192 (tens of KB), sent when you join or change it, relayed by the host and given to anyone who joins later. It only reaches members of the same room and is dropped when you leave. One new message type was added; the frame format and protocol version are unchanged, so a 1.1.0 host simply will not relay pictures.

### Digits and fonts

Persian digits used to be produced by WPF's own number substitution, which also rewrote the decimal point into a character no font contains — IP addresses showed boxes, and the same happened under a Persian Windows. Text now always stays ASCII; Persian digits are drawn by a digits-only font (cut from Vazirmatn). IPs, ports and codes are always Latin with their dots, and Windows' display language and regional format no longer reach the interface. In chat, Persian messages get Persian digits (if enabled) and English messages keep what was typed. Digits typed on a Persian keyboard are converted where a number is expected.

### Fixes

Clicking message text no longer throws `'Paragraph' is not a Visual or Visual3D`. Microphone and speaker at 0% turn grey instead of drawing a red cross. The "123 Latin" label no longer turns Persian. Volume percentages use the app's own face.

### Emoji

The bundled set is unchanged. Put your own images in `%LOCALAPPDATA%\VirtualLANPlatform\emoji` (file name = hex code point, e.g. `1f600.png`) to replace any of them without reinstalling.

### Install

Run `VirtualLANPlatform_Setup_v1.2.0.exe` over an existing install; settings are kept. Windows 10 1809 or later, 64-bit; the installer fetches the .NET 8 Desktop Runtime if it is missing. SHA-256:

```
9C81A0724ECBB2DCED404E664A13883E59F2DBAA330D0A4E2A2C43CE09B931D2
```

</details>
