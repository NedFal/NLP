
را از روی فایل میخوانیم. این دیتاست ⅽorpus در ابتدا کتاب خانه های لازم را نصب و ایمپورت میکنیم. سپس دیتاست
شامل لغات فارسی است که از کورپسهضم بدست آمده است. سپسریشه کلمات موجود در دیتاست را به دیتاست اضافه میکنیم،
در حذف آنها به خوبی عمل ⅼeⅿⅿatizer همچنین به انتهای اسم ها و صفت ها در دیتاست پسوندهایی را اضافه میکنیم زیرا گاها
نمیکند.
سپس در قسمت بعدی یک دیکشنری از ابزار های لازم میسازیم.
آن فرایند تشخیص کلمات خارجی را انجام میدهیم. برای اینکار ⅾeteⅽt و در تابع foreignWorⅾⅮeteⅽtor سپس در کلاس
ابتدا جملات متن ورودی را استخراج میکنیم، سپس آن ها را نرمالایز میکنیم، با کمک لمتایزر کتابخانه دادما ، ریشه کلمات را
بدست می آوریم و با آن ها جایگزین میکنیم.
از انجایی که فعل ها صرف های مختلف دارند و لمتایزر گاها برای آن ها دچار مشکل میشود و همچنین از آنجایی که دیتاست همه
کتابخانه هضم ، فعل ها را تشخیصمیدهیم و آن ها را از لیست کلمات حذف میکنیم. posTagger فعل ها را ندارد ، با کمکمدل
سپس برای کلمات بدست آمده بررسی میکنیم که آیا این کلمه در کورپس وجود دارد یا نه، اگر وجود نداشت آن را به عنوان کلمه
انگلیسی در نظر میگیریم و به دیکشنری خروجی اضافه میکنیم.
میسازیم و با ورودی گرفتن جمله از کاربر کلمات خارجی آن را foreignWorⅾⅮeteⅽtor یک نمونه از run سپس در تابع
استخراج میکنیم.
ایده دیگری که این تمرین به سمت آن رفتیم، استفاده از فونتیک کلمات انگلیسی و ساختن فرم فارسی کلمات انگلیسی با استفاده
از آن هاست.
و فونتیک متناظر آن ها را در لیست worⅾs برای اینکار ابتدا دیکشنری انگلیسی را لود میکنیم و کلمات انگلیسی را در لیست
ذخیره میکنیم. phoniⅽsⅬist
سپس با استفاده از یک دیکشنری که در آن شکل فارسی برای هر فونتیک نوشته شده است ، شکل نوشتاری فارسی کلمات را
بدست می آوریم.
شکل فارسی نوشتاری آن ها قرار گرفته است. persianizeⅾ، کلمات انگلیسی و در لیست ، worⅾs پس از پایان اینکار در لیست
که ساختیم ⅾeteⅽtor یک متن را به عنوان ورودی میگیریم و کلمات انگلیسی آن را به کمک ای ⅽhangeEngⅼishWorⅾ در تابع
به شکل انگلیسی میبریم و سپسترجمه آن ها را بدست می آوریم و به جای googⅼetrans پیدا میکنیم و آن ها را به کمک کتابخانه
آن ها جایگزین میکنیم.
یک ایده هم این است که به کمک همان لیست نوشتار فارسی کلمات انگلیسی که آن ها را بدست آوردیم ، هر کلمه خارجی پیدا
شده را در متن ورودی را در آن لیست پیدا کنیم و شکل انگلیسی آن را به این شکل بدست آوریم و سپس آن را ترجمه کنیم. البته
باید به این نکته توجه کنیم که گاها بعضی کلمات به درستی به فارسی نوشته نمیشوند persianizeⅾ در جستجو کلمه در لیست
به صورت کمپیوتر خوانده میشود ولی در فارسی کامپیوتر نوشته میشود، برای رفع این مشکل میتوان ⅽoⅿputer برای مثال کلمه
شدن ”آ” را کم در نظر بگیریم زیرا بسیاری از اوقات فونتیک ”شوا” insert استفاده کنیم و برای مثال هزینه ⅾistanⅽe eⅾit از
در فارسی به درستی رعایت نمی شود و به جای آن ”آ” نوشته میشود.
به googⅼetrans را بدست آورد، که از آنجا که کتابخانه persianizeⅾ با اینجور ایده ها میتوان شکل انگلیسی کلمات لیست
خوبی نتیجه میدهد و همچنین کمبود زمان، اینکار را انجام ندادیم.
گاهی ممکن است برخی کلمات هم در زبان فارسی وجود داشته باشند هم در زبان انگلیسی. برای اینکه فرم درست کلمات
را تشخیص دهیم، یک بار کلمه را فارسی در نظر میگیریم و بار دیگر کلمه را انگلیسی در نظر میگیریم و معادل فارسی اش را به
و با مدل زبانی هضم، میبینم که کدام جمله محتمل تر ⅽosinesiⅿiⅼarity کمک روش گفته شده جایگزین میکنیم. حال به کمک
است.

resources can be found in:
https://drive.google.com/drive/folders/1wMezp_Dval3rm4Ji2MGNIbIO7QqlDAnR?usp=sharing



# Foreign-word detector
## Sharif University of Technology <br/> CE Dept. <br/> NLP Course<br/> Dr. E. Asgari

**People involved**:<br/>
>Amirahmad Shafiee<br/>
>Neda Fallah<br/>
>Ali Shafiei

**Description**: Language borrowing is one of the important topics in the linguistic world. Aside from it's positive and useful effects on the destination language; uncontrolled borrowing of foreign words may cause irrepairable harm. This brings up the idea behind the task.

**Notebook**: Mian product of the notebook is **Foreign_word_detector** function. the detector works based on the root of the words. Upgraded form of the functoin can be further found in the notebook; utilizing the *word distance measuring* along-side with persianizing the foregin words(writing the persian forms of foreign words with the help of phonetics) led to a better performing form of funciton.

**Tags**:
* Edit distance
* Lemmatization
* Text preprocessing
* Language borrowing
* Indirect translating
