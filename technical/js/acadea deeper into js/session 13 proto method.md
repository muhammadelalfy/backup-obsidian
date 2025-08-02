فى حاجه اسمها constructor method 
مش اللى داخل الكلاس 
دى بعرفها اول حرف فيها كابيتال وزيها زى الكلاس بقدر اعمل منها اوبجكت 

function Person(name, age) {
  // Properties
  this.name = name;
  this.age = age;

  // Method
  this.sayHello = function () {
    console.log(`Hello, my name is ${this.name}`);
  };
}


هى نفسها دى بس اللى فوق الطريقه القديمة 

class Person {
  constructor(name, age) {
    this.name = name;
    this.age = age;
  }

  sayHello() {
    console.log(`Hello, my name is ${this.name}`);
  }
}


اقدر اضيف فى الاتنين shared mehtods عن طريق prototype 

function Person(name, age) {
  this.name = name;
  this.age = age;
}



Person.prototype.sayHello = function () {
  console.log(`Hello, my name is ${this.name}`);
};


كل حاجه فى js عباره عن اوبجكت ما عدا null , undefined 

'dad'.__ proto __ 
كل كلاس او constructor mehod داخله اوبجكت اسمه  proto
هتطبع ال prototype object

كل اوبجت جواه ال    proto type built in  property 
ال proto type object جواه ال constructor اللى بيشاور على الاوبجت 

ال prototype property بتشاور على ال prototype object فى ال constructor function او ال class وبتكون موجوده فى الاوبجكت اللى معمول من 

ال constructor اللى داخل ال prototype object بيشاور على ال ال constructor function او ال class اللى هو داخله 

بستفاد من كدا ان اى اوبجكت شايف ال proto type بتاع الاب فلو ضفت فيه ميثود كل الاوبجكتات هتشوفها 

![[Pasted image 20250730093019.png]]

الطريقة التانيه هنا احسن لان الاولى كل اوبجت هيتكريت معاه ميثود جديده اسمها drive لكن فى ال proto لا 

البروتو تايب بروبرتى بتشاور على البروتوتايب اوبجكت والبروتوتايب اوبجكت فيه كونسترؤفخق الكونستركتور بتشاور على الاوبجكت اللى هى جواه 

![[Pasted image 20250802211329.png]]

البروتو تايب اوبجكت متشارك فى كل الانستانسز 
هنا عملت اتنين اوبجكت والناتج بشاركو نفس البروتوتايب اوبجكت 

اى اوبجكت فى ال js وارث من  Object وال __proto__ بتاعته ب null لان هو الاب والروت مفيش حلجه اعلى منه 

#prototype_chain 

const name = "ali"

        console.log(name.__proto__.__proto__.__proto__)
كدا لجيب ال string ومنه بجيب ابوه اللى هو الاوبجكت الروت ومن الاوبجكت الروت بجيب ال proto بتطلع null لان مفيش حاجه فوقه 

لما بستدعى فانكشن فى js بيروح يدور عليها فى الاوبجت القهاش بطلع يدور فى الاب ملقهاش بطلع يدور فى الاب لحد ما يوصل للروت اللى هو الاوبجت Object 

لو عاوز اضيف ميثود تتقرا فى اى اوبجكت فى ال js بطيفها فى ال Object 

Object.prototype.hey = function(){
	console.log('hey') 
}

const arr = new Array()
arr.hey() => prints hey 


الكونستركتور فانكشن او الكلاس هم اللى بتطبع اللى جواهم عن طريق ال prototype 

اما الاوبجكت بتطبع اللى فوقه عن طريق __ proto __ يعنى بتطبع ال prototype بتاع اللى فوقه 



	class Person{}

        class Student extends Person {

        }

        console.log(Student.prototype)

![[Pasted image 20250802222234.png]]

 console.log(Student.prototype.____proto___)

![[Pasted image 20250802222444.png]]



