
<h2 dir="rtl"> زمان‌یار / ZamanYar</h2>


[![ZamanYar Preview](https://amir8218.ir/GitHub/ZamanYar/Screenshot/ZamanYar.png)](https://amir8218.ir/GitHub/ZamanYar/Project/)
---

<h2 dir="rtl">  درباره / About </h2>


زمان‌یار نتیجه‌ی دغدغه‌ی من برای ساده‌تر کردن انتخاب زمان در فرم‌های وب فارسیه. <br>
از اونجایی که `input` با `"type="time` تو خیلی از مرورگرها رابط کاربری خوبی برای فارسی‌زبان‌ها نداره، <br>
تصمیم گرفتم یه ابزار کوچیک، سبک و فارسی‌پسند بسازم که کارو برای کاربر و برنامه‌نویس راحت‌تر کنه. <br>
زمان‌یار یه جایگزین ساده، کاربردی و بومیه برای انتخاب ساعت، با ظاهری سازگار با سلیقه‌ی ما ایرانی‌ها. <br>
 

<details>
<summary>English (click to expand)</summary> <br>

ZamanYar was created from my personal goal to make time selection easier in Persian web forms. <br>
Since the default `input` `type="time"` doesn't offer a good user interface in many browsers for Persian users, <br>
I decided to build a small, lightweight, and Persian-friendly tool to simplify the process for both users and developers. <br>
ZamanYar is a simple, practical, and local alternative for picking time, designed to match the aesthetics and preferences of Iranian users. <br>



</details>

---
<h2 dir="rtl"> قابلیت‌ها / Features </h2>

- انتخاب سریع و دقیق زمان
- نمایش پیش‌فرض ساعت فعلی
- جایگزینی کامل تایپ دستی در input‌های زمان HTML
- پشتیبانی کامل از فرمت و زبان فارسی
- طراحی ساده و کاربرپسند
- نصب سریع و آسان
- کاملاً ریسپانسیو و سازگار با همه دستگاه‌ها
- بدون نیاز به فونت خارجی – از فونت پروژه شما استفاده می‌کند
- مناسب برای وب‌سایت‌های فارسی‌زبان و ایرانی


<details>
<summary>English (click to expand)</summary> <br>

- Quick & precise time selection Displays current time by default
- Fully replaces manual time input in HTML
- Full support for Persian format and language
- Clean, user-friendly design
- Fast and easy to install
- Fully responsive and device-optimized
- No external fonts – inherits your project’s typography
- Perfect for Persian and Farsi-language websites



</details>

---
<h2 dir="rtl"> تست آنلاین / Live Demo </h2>

برای تست آنلاین می‌توانید از این لینک استفاده کنید: 

<a href="https://amir8218.ir/GitHub/ZamanYar/Project/" target="_blank" style="background-color:#4CAF50;color:white;padding:10px 20px;text-decoration:none;border-radius:5px;">تست آنلاین زمان‌یار</a>

<details>
<summary>English (click to expand)</summary> <br>

You can try the live demo here:  

<a href="https://amir8218.ir/GitHub/ZamanYar/Project/" target="_blank" style="background-color:#4CAF50;color:white;padding:10px 20px;text-decoration:none;border-radius:5px;">Test ZamanYar Online</a>


</details>

---

<h2 dir="rtl"> نحوه استفاده / How to Use </h2>


#### ○ استفاده به روش `Include`:

1. آخرین نسخه فایل `ZamanYar.js` را از پوشه `script` دانلود کنید.  
2. فایل را داخل پوشه پروژه خود قرار دهید.  
3. در فایل `HTML` پروژه، اسکریپت را با این کد اضافه کنید:
```html
<script src="script/ZamanYar.js" defer></script>
```
4. حالا به هر `input` که کلاس `ZamanYar` بدهید اسکریپت روی ان اجرا میشود. نمونه:
```html
<input type="text" class="ZamanYar" placeholder="انتخاب ساعت"/>
```

<details>
<summary>English (click to expand)</summary> <br>
 
### ○ Using via Include:
 
1. Download the latest version of the `ZamanYar.js` file from the `ZamanYar.js` folder.  
2. Place the file inside your project folder.  
3. Add the script to your project's `HTML` file with this code:
```html
<script src="script/ZamanYar.js" defer></script>
```
4. Now, add the class `ZamanYar` to any `input` element where you want the script to apply. Example:
```html
<input type="text" class="ZamanYar" placeholder="Select Time"/>
```

</details>

#### ○ استفاده به روش `CDN`: <br>

1. در این روش بدون نیاز به دانلود، با یک خط کد می‌توانید فایل را به‌صورت آنلاین در `HTML` خود وارد کنید. <br>
2. همچنین در این روش می‌تونید از یه نسخه خاص استفاده کنید یا همیشه آخرین نسخه رو داشته باشید. <br>
3. برای استفاده از یک نسخه خاص، به جای `v1.0.0` ورژن دلخواه‌تون رو بذارید. <br>

⚠️ فقط در صورت اتصال به اینترنت قابل استفاده است.



نسخه آخر (داینامیک):
```html
<script src="https://cdn.jsdelivr.net/gh/Amir-Hosein-Amiri/ZamanYar@main/script/ZamanYar.js"></script>
```
نسخه انتخابی (ثابت):
```html
<script src="https://cdn.jsdelivr.net/gh/Amir-Hosein-Amiri/ZamanYar@v1.0.0/script/ZamanYar.js"></script>
```

<details>
<summary>English (click to expand)</summary> <br>

### ○ Using via CDN: <br>

1. With this method, you can include the file online in your HTML with a single line of code, no download needed. <br>
2. You can either use a specific version or always have the latest version. <br>
3. To use a specific version, replace v1.0.0 with your desired version. <br>

⚠️ Only works when connected to the internet.

Latest version (dynamic):

```html
<script src="https://cdn.jsdelivr.net/gh/Amir-Hosein-Amiri/ZamanYar@main/script/ZamanYar.js"></script>
```

Specific version (static):

```html
<script src="https://cdn.jsdelivr.net/gh/Amir-Hosein-Amiri/ZamanYar@v1.0.0/script/ZamanYar.js"></script>
```

</details>

<h2 dir="rtl"> حمایت / Support </h2>

اگر از زمان‌یار خوشتان آمد و مایلید پروژه را توسعه دهیم، لطفاً با دادن ⭐ به این پروژه و به اشتراک گذاشتن آن ما را حمایت کنید.  
حمایت شما انرژی و انگیزه‌ای برای بهبودهای بیشتر است.

<details>
<summary>English (click to expand)</summary> <br>

If you like ZamanYar and want to see it improved, please support us by starring ⭐ this repository and sharing it.  
Your support gives us energy and motivation for further improvements.

</details>

---

<h2 dir="rtl"> ارتباط با من / Contact Me </h2>

 <p dir="auto">
    <a href="https://wa.me/+989201342023" rel="nofollow"><img src="https://img.shields.io/badge/WhatsApp-url?style=for-the-badge&logo=WhatsApp&logoColor=%2325D366&color=%23082032" alt="WhatsApp" style="max-width: 100%;"></a>
    <a href="https://www.instagram.com/amir._.ea_" rel="nofollow"><img src="https://img.shields.io/badge/instagram-%23082032?style=for-the-badge&logo=instagram&logoColor=%23FD0AB6&color=%23082032" alt="Instagram" style="max-width: 100%;"></a>
    <a href="https://t.me/Ami_ea" rel="nofollow"><img src="https://img.shields.io/badge/telegram-url?style=for-the-badge&logo=telegram&logoColor=%232CA5E0&color=%23082032" alt="telegram" style="max-width: 100%;"></a>

