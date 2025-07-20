
const car = {
var1: red , 
var2: green
}

{var1 , var2} = car
console.log (var1) works 

كدا خزنت القيم مباشرة فى متغيرات 

{var1: , var2} = car

لازم بنفس اسم ال propery فى الاوبجكت يا اما اغيره كدا 
{var1: var3, var2} = car
دلوقت بقى val 3 بيشاور على var1  اللى جوه الاوبجكت 

ممكن استخدم ال rest operator فى destructing array 

const fruits = ['banana' , 'orange' , 'strawberry']

const [banana , orange , ...other] = fruits

log(other) => strawberry 

اقدر استخدم ال array destructing فى swapping 

[a,b] = [b,a]




