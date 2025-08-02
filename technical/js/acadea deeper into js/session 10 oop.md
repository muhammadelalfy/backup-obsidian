لو عملت set لفاليو مش متعرفه فى بروبرتى بتشتغل عادى دا فى الكونستركتور

class Car{

	name = 'ali'
	
	constructor(name , brand){
	
		this.name = name;
		
		this.brand = brand;
		
		console.log(name , brand)
	
	}

}

let car1 = new Car('bmw' , 'any');

---
فيه طريقتين لكتابة الميثود 


class Car{

name = 'ali'

drive(){

console.log('drive')

}

stop = function(){
console.log('stop')

	}

}


let car1 = new Car('bmw' , 'any');

car1.drive();

		car1.stop()

لو عاوز اضيف ميثود فى كلاس عد ما عرفته بستخدم ال prototype 

Car.prototype.start = function(){
console.log()
}

