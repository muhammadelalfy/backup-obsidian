       

2
[2:54](https://www.youtube.com/watch?v=xpFNbKYzzfU&list=PLtFbQRDJ11kFJFzd5UNy5vSnkbR031vG9&index=6&t=174s) Colors [7:54](https://www.youtube.com/watch?v=xpFNbKYzzfU&list=PLtFbQRDJ11kFJFzd5UNy5vSnkbR031vG9&index=6&t=474s) class & id [12:18](https://www.youtube.com/watch?v=xpFNbKYzzfU&list=PLtFbQRDJ11kFJFzd5UNy5vSnkbR031vG9&index=6&t=738s) display [25:54](https://www.youtube.com/watch?v=xpFNbKYzzfU&list=PLtFbQRDJ11kFJFzd5UNy5vSnkbR031vG9&index=6&t=1554s) visibility [29:39](https://www.youtube.com/watch?v=xpFNbKYzzfU&list=PLtFbQRDJ11kFJFzd5UNy5vSnkbR031vG9&index=6&t=1779s) position [1:08:53](https://www.youtube.com/watch?v=xpFNbKYzzfU&list=PLtFbQRDJ11kFJFzd5UNy5vSnkbR031vG9&index=6&t=4133s) float [1:21:17](https://www.youtube.com/watch?v=xpFNbKYzzfU&list=PLtFbQRDJ11kFJFzd5UNy5vSnkbR031vG9&index=6&t=4877s) opacity [1:26:04](https://www.youtube.com/watch?v=xpFNbKYzzfU&list=PLtFbQRDJ11kFJFzd5UNy5vSnkbR031vG9&index=6&t=5164s) nesting [1:30:21](https://www.youtube.com/watch?v=xpFNbKYzzfU&list=PLtFbQRDJ11kFJFzd5UNy5vSnkbR031vG9&index=6&t=5421s) Grouping [1:33:45](https://www.youtube.com/watch?v=xpFNbKYzzfU&list=PLtFbQRDJ11kFJFzd5UNy5vSnkbR031vG9&index=6&t=5625s) pseudo classes [1:37:37](https://www.youtube.com/watch?v=xpFNbKYzzfU&list=PLtFbQRDJ11kFJFzd5UNy5vSnkbR031vG9&index=6&t=5857s) pseudo elements [1:47:08](https://www.youtube.com/watch?v=xpFNbKYzzfU&list=PLtFbQRDJ11kFJFzd5UNy5vSnkbR031vG9&index=6&t=6428s) selector

3
[0:36](https://www.youtube.com/watch?v=HtYGgEuiG8o&list=PLtFbQRDJ11kFJFzd5UNy5vSnkbR031vG9&index=7&t=36s) Attr selector [5:24](https://www.youtube.com/watch?v=HtYGgEuiG8o&list=PLtFbQRDJ11kFJFzd5UNy5vSnkbR031vG9&index=7&t=324s) Universal selector [9:08](https://www.youtube.com/watch?v=HtYGgEuiG8o&list=PLtFbQRDJ11kFJFzd5UNy5vSnkbR031vG9&index=7&t=548s) Navbar [18:01](https://www.youtube.com/watch?v=HtYGgEuiG8o&list=PLtFbQRDJ11kFJFzd5UNy5vSnkbR031vG9&index=7&t=1081s) Dropdown [26:34](https://www.youtube.com/watch?v=HtYGgEuiG8o&list=PLtFbQRDJ11kFJFzd5UNy5vSnkbR031vG9&index=7&t=1594s) CSS form [33:15](https://www.youtube.com/watch?v=HtYGgEuiG8o&list=PLtFbQRDJ11kFJFzd5UNy5vSnkbR031vG9&index=7&t=1995s) After & Before [40:34](https://www.youtube.com/watch?v=HtYGgEuiG8o&list=PLtFbQRDJ11kFJFzd5UNy5vSnkbR031vG9&index=7&t=2434s) CSS units [48:15](https://www.youtube.com/watch?v=HtYGgEuiG8o&list=PLtFbQRDJ11kFJFzd5UNy5vSnkbR031vG9&index=7&t=2895s) Gallery [51:46](https://www.youtube.com/watch?v=HtYGgEuiG8o&list=PLtFbQRDJ11kFJFzd5UNy5vSnkbR031vG9&index=7&t=3106s) More about nesting [56:58](https://www.youtube.com/watch?v=HtYGgEuiG8o&list=PLtFbQRDJ11kFJFzd5UNy5vSnkbR031vG9&index=7&t=3418s) Specificity

مشكلة الفلوت انه بيخلى البيرنت مش حاسس بالابناء اللى جواه 
 البادينج بياثر فى الويدس والهايت بتاع العنصر 
 
لو البادنج اشتغل يمين وشمال بس يبقى ده inline 
بحوله block لو عاوز يشتغل من كل الاتجاهات


###### الفرق بين العنصر `inline` و `inline-block` في CSS 1. **inline**: - العناصر من نوع `inline` لا تبدأ سطر جديد (تظل في نفس السطر مع العناصر الأخرى). - لا يمكنك تحديد `width` أو `height` للعناصر من نوع `inline`. - تأخذ العناصر المساحة التي تحتاجها بناءً على محتواها فقط. - بعض الأمثلة على العناصر من نوع `inline`: `<span>`, `<a>`, `<strong>`, `<em>`. ```html <span>عنصر 1</span> <span>عنصر 2</span>

1. **inline-block**:
   - العناصر من نوع `inline-block` تتصرف مثل العناصر من نوع `inline` (لا تبدأ سطر جديد).
   - ومع ذلك، يمكنك تحديد `width` و `height` لهذه العناصر.
   - يتيح لك هذا التحكم في حجم العنصر مع الإبقاء على تصرفه كعنصر `inline`.
   - بعض الأمثلة على العناصر من نوع `inline-block`: `<img>`, `<button>`, أو أي عنصر تقوم بتعيين `display: inline-block;` له.


2. **inline**: - العناصر من نوع `inline` لا تبدأ سطر جديد (تظل في نفس السطر مع العناصر الأخرى). - لا يمكنك تحديد `width` أو `height` للعناصر من نوع `inline`. - تأخذ العناصر المساحة التي تحتاجها بناءً على محتواها فقط. - بعض الأمثلة على العناصر من نوع `inline`: `<span>`, `<a>`, `<strong>`, `<em>`. ```html <span>عنصر 1</span> <span>عنصر 2</span>

الفلوت بيخلى الخليفة بتاع الاب مش ظاهرة بتعمل طريقة clear 

لو الاب اسليوت او ريلاتيف او فيكسد والابن ابسليود برده الابن هيتحرك بالنسبه للابل

الاخفاء ب display none  او visibilty hidden 
---------------------------------------------------------

.nav > ul > :nth-child(2) a:hover + ul{

    display: block;

}
هات الاخ بتاع ال a اعمله ظهور


عاوز اختبر عنصر انلاين ولا انلاين بلوك
هتعطيله  باك جراوند لو جيت على اد العنصر هختبر بالويدث لو خدته انلاين بلوك لو مخدتوش يبقى انلاين 
-------------------------------------------------------------
لو عاوز توسطن عنصر انلاين بلوك بتعمل vertical align 
  

.list::before{

    width: 10px;

    height: 10px;

    background-color: red;

    vertical-align: middle;

}
-----------------------------------------------------
اى عنصر بياخد فونت سايز 16 بيكسل 

الوحدات 
em relative to parent
اضربه فى الفونت سايز بتاع الاب 

rem relative to root (html)

vw , vh يعنى view port 

10vh يعنى 10فى الميه من ارتفاع الشاشه سواء موبايل او غيره كذلك العرض
مفيده فى الريسبونسيف 
------------
p.item
لازقه كدا هات العنصر بي اللى واخد كلاس اتيم 
 او اى برجراف واخد كلاس اتيم
.item.clor.any
هات اى عنصر واخد التلاته كلاس دول مع بعض 
-----
specificity
الولوية
ليها معادلة 

inline-style id|class-psoudo class- attribute selector | element 

اكتب المعادله للمثال ده 
div .item p
inline-style id|class-psoudo class- attribute selector | element 
	0         0    1 2 = 12

فيه كام عنصر وكام اى دى وهكذا

![[Pasted image 20250306224325.png]]
![[Pasted image 20250306224529.png]]

------
اول اخ + 
كل الاخوة ~

انواع ال SELECTORS

اعنصر 
الكلاس 
الاى دى 
< ~ , +

----
اى عنصر عنده اتربيوت ديمو

[class="demo"]
اى ديف واخد اتربيوت ديمو

div[class="demo"]

---
margin:auto وسطن العناصر البلوك
text-align : center وسطن النص او وسطن النص داخل العنصر 
margin-left: auto انقله لليمين والعكس صحسح
---
inline فى نفس السطر مبياخدس ويدث او هايت
- block عرضه 100%  بياخد مساحة من كل الاتجاهات العناصر تحت بعض
- inline-block المساحه بتكون من جميع الاتجاهات وبيكون نفس السطر 
عشان اختبر بعطى باك جراوند لو اخدت الصفحة يبقى بلوك لو جت على قد العنصر يبقى اختبر بعطى عرض لو جه على قد العنصر يبقى inline لو اخد الويدث يبقى inline-block

-----

الفرق بين ال margin . padding

margin  
المسافة بين العنصر واللى جمبه
بياخد قيم بالسالب
مبياثرش على العرض والطول بتوع العنصر

padding
المسافة بين العنصر والبوردر بتاعه 
مبياخدش قيم بالسالب 
بياثر على العرض والطول بتوع العنصر 

----
العلاقة بين البوردر والبادينج الاتنين بياثرو فى حجم وطول العنصر من جميع الاتجاهات 

خد العرض الحقيقى والطول للعنصر من ال inspect مش من styles 
![[Pasted image 20250307120329.png]]



----
الفرق بين ال absolute , relative 

absolute 
العنصر بتحرك بالنسبة للصفحة

relative 

العنصر بتحرك بالنسبة لنفسه الtop , right , left , bottom بيكون كله صفر 

الاتنين مع بعص ال absolute مع الابن يعنى اتحرك بالنسبه للاب

---
margin:auto 
مش بتشتغل مع العناصر ال inline , inline-block

بتشتغل مع العناصر ال block ومعناها توسيط العناصر

----
العلاقة بين ال inline-block , text-align:center
العنصر بلوك معناه انه واخد السطر كله يتحرك فيه 
العنصر inline , inline-block معناه انه واخد مكانه بس ما اعرفش اعطيه مارجن اوتو 

----
العناصر ال inline , inline-block بتوسطنهم بانك تعطى لابوهم text-align center 

---
الفرق ببين ال inline-block , float
الفرق فلا الفونت سايذ الفلوت ممعهاش والتانيه معاها لو عاوز اشيله بعمل بيرنت واعطيه الفونت سايز بصفر او الزق العناصر فى بعض فى الاتش تى ام ال 

---
ال display none بيختفى وبيشيل مكانه من الصفحة 
ال visibility hidden بيختفى ومش بتشال من الصفحة 

---
ال position fixed , absolute بيحولو العنصر من بلوك ل انلاين بلوك 

----
visibilty:hidden
opacity :0 بتخفى 

----
هيرو اماج بيسنتر الديف 

---

