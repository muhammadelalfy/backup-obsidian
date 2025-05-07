 خصائص بحطها لعناصر الفيرجن 3 اللى مبتشتغلش على المتصفحات القديمة عشان تشتغل 
![[Pasted image 20250314213050.png]]

----
مع عقارب الساعه اماكنهم توب لفت توب رايت بوتم رايت بوتم لفت 

![[Pasted image 20250314213616.png]]

---
فيه نوعين من ال background size ال 
cover fill all screen affect image with pixels make zoom 
content take screen to specific size 

---
there are 3 types for 
background-origin 
padding-box 
border-box
content-box 

نفس الكلام 
background-clip 
background-origin 
padding-box 
border-box
وهى افضل 
المساحة الزرقا بتبقى هى ماحة العنصر الاصلية 

![[Pasted image 20250314220511.png]]

----
box shadow
![[Pasted image 20250314220852.png]]

انست يعنى هتظهر جوه ولات بره 
اسبريد الانتشار 


-----

![[Pasted image 20250314221103.png]]

ممكن اعمل اكتر من ظل كدا وبيكون مع العناصر البلوك 

---
![[Pasted image 20250314221215.png]]دى خصائص النصوص 

---
![[Pasted image 20250314221644.png]]

الgradient 
عندى نوعين .. linear , radilal دائرى 
ممكن اقوله ابدأ من top left . top right 

وبعد كدا بعطيله الالوان وممكن اكتب جمب اللون نسبة ظهوره 

yellow 50% , green 30 % 

الradial فيه منه 3 انواع 
![[Pasted image 20250314221952.png]]

ابدا ب 50 من الواى و 20 من الاكس 

الانواع 
	circle 
	closest-corner 
	farthest-corner
	
----

word-wrap : break-word / break-all بتكسرالكلمة مرتين 

----
transform: traslate (x , y ) حرك فى اتجاه الاكس والواى ولو كتبت قيمة واحده معناها اكس 
transform: rotate(50deg) لف العنصر 

---
transform: scale(x , y )

لو كتبت قيمة واحده هياخدها من الاتجاهين 

transform:skew(50deg) لف من ناحية الاكس بس 

50deg , 30 deg  من ناحية x , y 
 بمسيل العنصر بشده وبخير شكله مش بلفه 

---
فى ال 3d ال transorfm-translate-z مش بتشتغل الا مع ال rotate 

---
عشان الشكل يشتغل معايا 3d بعطى الاب بروبرتى اسمها perspective:600 مثلا 

---
matrix 3d 

بتتعمل عن طريق موقع matrix 3d generator عشان بتاخد 16 قيمة 

---
perspective-origin: left top 

بتحدد الشكل هيبدا منين كثلاثى ابعاد 

---
transform-origin : top right 
transform: rotate(50 deg)
بتحدد هيبدأ لف او تحرك ك traslate منين بالظبط بحدد النقطة اللى هيلف من عندها 


---
transform-style : preserve-3d / flat
بتتحط للاب عشان يظهر الابناء 3 د 

ال flat لل 2 د 

---
فى ال 3d كل عنصر له فرونت فيس وباك فيس  
لو عاوز اخفى خلفيته 
backface-visibility : hidden / visible 

---
![[Pasted image 20250315151342.png]]

الاوفر فلو بتحكم فيه فى الاسكرول يظهر ولا لا له 3 انوع 
visible , hidden , scroll 

----
opacity 
بتاخد قيم من صفر ل 1 

---
خاصية ال resize: horizontal / vertical / none 
بستخدمها مع النصوص مثلا 

---
![[Pasted image 20250315152132.png]]

![[Pasted image 20250315152144.png]]

الاوتلاين ده البوردر اللى فوق البوردر اما الاوتلاين اوفست المسافة بين البوردر والاوتلاين 

---

لو عاوز اعمل بادينج وبوردر ومش عاوزهم ياثروا على ال width عشان ال float ميضربش 
 
 بعمل الخاصية دى عالعنصر نفسه 
 border-sizing:border-box 

---
trsnsition الانتقال 

![[Pasted image 20250315152932.png]]

البروبرتى بحدد هيتعمل على ايه فى الهوفر والديوراشن المدة 
ممكن اعطى البروبرتى all طبق على كل اللى فى الهوفر 

![[Pasted image 20250315153732.png]]

كستم اكتر كل واحده فى مدة اد ايه 

---
transition timing function 

![[Pasted image 20250315154015.png]]

linear يمشى بنفس السرعة 
ease يبدا براحه يسرع ينهى براحه 

ease out ينهى براحه 
ease in يبدا براحه 
ease in out يمشي كله براحه 

----
![[Pasted image 20250315170828.png]]

اخر واحده دى ال delay هيتاخر اد ايه اما يبدا اصبر 3 ث وابدا 

---
animation 

بعملها بتعريف كيفريم 
لازم duration يتحط 

![[Pasted image 20250315172722.png]]

لو قيمتين بس اللى بتغيرو بستخدم from to اكتر بستخدم الطريقة اللى فى الصورة 

---
فى حاجه اسمها ال steps فى ال transition 

---
![[Pasted image 20250315173039.png]]

ال count عدد مرات تكرار الانيميشن 
لو الى مالا نهاية infinite 
 وال timing function نفس اللى فاتت بنفس القيم بتاع ease 
 
 ال delay اصبر كذا ث وابدا 
 ال direction 
 alternate 
 alternate -reverse 
 reverse 
 normal

---
animation fill mode : 
forward اشتغل واقف عند اخر انيماشين 
backword اشتغل وارجع وخد اول انيميشن حتى لو مش 

both اجمع بين الخاصيتين شغل اول انيميشن متراعيش ال delay واقف عند اخر انيميشن 

---
animation play state : paused 
بيوقف الانيميشن 

لو فى سطر واحد 
![[Pasted image 20250315175809.png]]

فيه موقعين بعمل عليهم الانيميشن 
css animation generator 
css keyframe 

----
css columns 

![[Pasted image 20250315180544.png]]

count عدد الاعمدة 
gap الفرق بينهم 
rule دا ال border بينهم بياخد نفس خصائص البوردر
span لو فيه عنصر جوه عاوزه ياخد كل الاعمده 
span: all 
width عرض الكولم كام

---
columns : 30px 3
قسمهم 3 وعرضهم 30 

---
