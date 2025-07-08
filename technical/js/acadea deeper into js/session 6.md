فيه نوعين من العمليات فى ال js 
sync الكود اللى بتنفذ لحظى
async الكود اللى بياخد وقت عشان يتنفذ وبحطه فى الخلفية 

ال js بتستخدم ال queue system فى ال async بستخدم نظام اسمه event loop 

setTimeout() دى async 

ال js بستخدم اوبجكت اسمه promise عشان يعمل ال async 

const iceCream = function (amount = 5) {

return new Promise(function (resolve, reject) {
	setTimeout(() => {
		if (amount == 5) {
		resolve('enough')
				}
		else {
		reject("not enough")
			}
		});
	})
}

iceCream().then((response) => {

	console.log(response)

}).catch((error) => {

	console.log(error)

})

ده مثال بستخدم ال promise بستقبل resolve فى حالة النجاح و reject فى حالة الفشل ودول دوال 
بستخدم settimeout عشان ال async , event loop 

اقدر استخدم then فى حالة النجاح واكتر من then وبتاخد برامتر بيمثل ال resolve function 
اقدر استخدم ال catch 

![[Pasted image 20250708115656.png]]

اللى بترجعه فى ال then تقدر تستقبله فى ال response فى ال then اللى بعدها 

ال catch بتشتغل مع ال thens اللى قبلها بس وممكن اغير مكان ال catch مش لازم تكون فى الاخر بس 

ال then بترجع كل مره اوبجكت promise  اقدر استدعى منه catch او then تانى 

ال catch مبترجعش اوبجكت promise 

ال catch بتستقبل ال throw new Error فى ال then اللى قبلها 
![[Pasted image 20250708121025.png]]

ال through error هتخلى ال catch اللى بعدها تشتغل وتستقبله
ولو عاملها وال error جاى من promise هيطبع ال promise error ومش هيطبع ال through لانه فى الحاله دى مش هيدخل اصلا ال then 





