# Novin-Test
اتصال و بارگزاری در برنامه ایتا از طریق api

# 1.ثبت نام
در ابتدا نیاز است که شما در برنامه ایتا ثبت نام کنید و یک حساب کاربری ایچاد کنید;
برای اینکار به لینک زیر مراجعه کنید و سیستم عامل مورد نظر را انتخاب کنید و حساب کاربری ایچاد کنید.
[لینک](https://eitaa.com/)

# 2.ایجاد کانال یا گروه
پس از ورود به برنامه و حساب خود، یک کانال یا گروه ایجاد کنید و گروه را در حالت عمومی قرار دهید و سپس یک ای دی برای آن انتخاب کنید
پس از ایجاد کانال به بحش تنظیمات آن رفته و در بخش ادمین ها یا مدیران، ایتایار را سرچ کنید و به ادمین ها اضافه کنید و سپس ذخیره کنید و خارج شوید.

# 3.دریافت لینک API TOKEN
پس از ثبت نام و ایجاد حساب کاربری به این [لینک](https://eitaayar.ir/admin/api) مراجعه کنید و وارد حساب خود در بخش مدیریت ایتا شوید
و سپس یک توکن ایجاد کنید و آن را کپی کنید
(این توکن امنیتی است و آن را در اختیار عموم قرار ندهید)

# 4.دریافت شناسه کانال/گروه
پس از ثبت نام و ایجاد حساب کاربری به این [لینک](https://eitaayar.ir/admin/peer/add) مراجعه کنید و وارد حساب خود در بخش مدیریت ایتا شوید
سپس از منو سمت راست به بخش افزودن کانال جدید مراحعه کنید و ای دی کانال و گروه خود را که از بخش اطلاعات ان برداشته اید را اضافه کنید و ثبت را بزنید.
پس از ثبت یکسری اطلاعات درباره کانال یا گروه ثبت شده نشان میدهد که شناسه آن نیز مشخص است که در ادامه به آن نیاز داریم.

# 5.ارسال و پست اطلاعات از طریق API
 در این قسمت شما ابتدا نیاز است تا fastapi را بر روی سیستم خود نصب کنید، کافیست کامند پایین را در ترمینال بش خود پیاده کنید
 ```bash
pip install fastapi
```

  و سپس برنامه ای که من نوشته ام را از گیت هاب من دریافت میکنید
```bash
git clone https://github.com/hosseink9/Novin-Test.git
```
پس از دریافت در ترمینال خود کامند زیر را ران کنید
```bash
uvicorn main:app --reload
```
پس از ران کردن آن به ادرس زیر بروید و با استفاده از swagger اطلاعات مورد نیاز خود را برای پست گذاشتن ارسال کنید
```bash
http://127.0.0.1:8000/docs
```

