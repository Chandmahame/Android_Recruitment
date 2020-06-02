# Android_Recruitment
&#x202b; 
پروژه چالش فنی اندروید-خرداد ۹۹

<div dir="rtl">

&#x202b;
# :شرح پروژه
<br>
&#x202b; 
چندماهمه برای خدمات بهتر به مشتریان، تصمیم گرفته اپلیکیشنی توسعه دهد که بتواند:
<br>
<ul>

&#x202b;

## :تسک اول

&#x202b; 
برنامه شامل دو اکتیویتی Home و Camera است.Camera اکتیویتی لانچر بوده و در اکتیویتی 
&#x202b; 
Camera، 
&#x202b; 
به محض وارد شدن دوربین باز شده و کاربر امکان ثبت عکس دارد.پس از ثبت و تایید عکس
گرفته شده، عکس باید در فولدری با نام Chandmahame در حافظه داخلی دستگاه ذخیره شود.پس
&#x202b; 
از آن برنامه بطور خودکار به اکتیویتی Home میرود.همچنین برای کلیک روی دکمه back (دکمه
&#x202b; 
مربوط به دستگاه) نیز برنامه باید به Home برود. در اینجا باید در یک بخش صرفا عکسهای موجود در
&#x202b; 
فولدر Chandmahame را در قالب recycler view و در یک بخش دیگر، یک recycler view از
&#x202b; 
خاطراتی که در این آدرس (https://base_url/diaries) وجود دارد را نمایش دهد.برنامه باید بتواند
&#x202b; 
عکسها را از imagePath  دانلود کرده و نمایش دهد(یعنی هر آیتم لیست recycler view مذکور، شامل
&#x202b;
یک عکس و یک متن
title خواهد بود). برای نمایش این دو بخش از Bottom Navigation استفاده می
&#x202b;
کنید یا Tab layout؟ چرا؟(در فایل Readme.md پروژه خود توضیح دهید)



&#x202b; 
قالب یک نمونه diaries در پاسخ URL فوق:

```
[

    {
    
        "id": 13,
	
        "imagePath": "https://base_url/bqHw1GPT6lxngcejPf7QWqKBsSFbHHn6vdQdLPKe.jpeg",
	
        "title": "Some titles",
	
    },
    {
	
        "id": 14,
	
        "imagePath": "https://base_url/bqHgw1GPT6lxngcejPf7QWqKBsSFbHHn6vdQdLPKe.jpeg",
	
        "title": "Some other titles",
	
    },   
]
```
</ul>


<ul>

&#x202b;
## :تسک دوم
&#x202b;
برنامه باید بتواند با استفاده از این آدرس
&#x202b; 
(https://base_url/notification) سیستم Pull notification را پیاده سازی کرده و هر یک ساعت یکبار چک کند که آیا نوتیفیکیشنی در پاسخ به این درخواست وجود دارد یا خیر.در صورت موجود بودن، نوتیفیکیشن باید تولید شود و
&#x202b; 
در صورت کلیک بر روی نوتیفیکیشن،بر اساس مقدار path، فرگمنت camera یا home باز شود.(مقدار path برابر با camera یا home خواهد بود)
&#x202b; 
آیا روش پیاده سازی شده توسط شما بر روی همه دستگاه ها به درستی کار می کند؟ اگر مشکلی وجود دارد راه حل برای آن پیشنهاد کرده و 
تولید کنید.



&#x202b;
قالب یک نمونه notification در پاسخ URL فوق:

```
{

	"id" : 3,
	
	"big_text": "Some big text!",
	
	"big_content_title": "Some big content title!",
	
	"summary_text" : "Some summary text",
	
	"content_title" : "Some content title",
	
	"path" : "camera"
}
```

</ul>

<ul>

&#x202b;
## :درباره پیاده سازی

&#x202b;
- تصمیم درباره جزییات بیشتر پیاده سازی و راه حل به عهده شماست، پس سعی کنید مناسب ترین پیاده سازی که فکر می کنید رو داشته
&#x202b; 
باشید. درباره جایی هم اگر ابهامی وجود دارد (علاوه بر امکان پرسش سوال از طریق ایمیل)، می توانید با توضیح دادن درباره ابهام 
&#x202b; 
مورد نظر در فایل Readme.md پروژه خودتون، از تصمیمی که گرفتید بگید و اینکه چرا.

&#x202b;
- کیفیت کد تولید شده (خوانا و تمیز بودن، تست نوشتن و…) و استفاده مناسب از گیت مهم است! 
</ul>

</div>

