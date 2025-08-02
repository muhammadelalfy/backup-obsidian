
![[Pasted image 20250720165022.png]]

نفس php  فى الوراثة 

---
الابن بياخد اللى وراثه الاب من ابوه يعنى الحفيد يقدر يقرا اللى فى الجد عن طريق الاب 

---
لو عاوز استدعى الكونستركتور من الاب للابن عن طريق super 

class Bmw extends Car{

constructor(name , brnad , magic){

super(name , brnad)

console.log(this.name , this.brand)

}

}