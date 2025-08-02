
object composition vs class inheritance 


ممتاز 👌  
سؤالك عن الفرق بين:

> 🔁 **Object Composition**  
> 🔗 **Class Inheritance**

هو من أهم المفاهيم في التصميم البرمجي، خصوصًا في JavaScript وLaravel وOOP عمومًا.

---

## 🧠 أولًا: تعريفات سريعة

### 🔁 **Object Composition**

> تركيب الوظائف عن طريق دمج خصائص/قدرات متعددة في كائن واحد باستخدام functions وليس classes.

const canEat = (state) => ({
  eat: () => console.log(`${state.name} eats.`)
});

const person = (name) => {
  const state = { name };
  return {
    ...canEat(state)
  };
};


🔗 **Class Inheritance**

إنشاء كلاس يرث من كلاس آخر (وكل خصائصه ودواله) باستخدام `extends`.


class Animal {
  eat() {
    console.log("eating");
  }
}

class Dog extends Animal {
  bark() {
    console.log("barking");
  }
}


## الفرق بين Object Composition و Class Inheritance

| المقارنة           | Composition (التركيب) | Inheritance (الوراثة)          |
| ------------------ | --------------------- | ------------------------------ |
| ✅ المرونة          | مرن جدًا              | أقل مرونة                      |
| 🔗 العلاقات        | لا توجد علاقة ثابتة   | علاقة هرمية ثابتة (is-a)       |
| 🔄 التوسعة         | سهل الإضافة والتعديل  | التوسعة قد تؤدي لتعقيد         |
| 🧩 إعادة الاستخدام | عبر دمج قدرات صغيرة   | عبر وراثة وظائف كاملة          |
| 🧠 التعقيد         | أبسط، بدون شجرة وراثة | قد يؤدي لـ "deep inheritance"  |
| 💥 مشاكل جانبية    | أقل coupling          | مشاكل عند تعديل الـ superclass |
| 🔒 الخصوصية        | state خاص عبر closure | الخصائص public/protected       |
| 📦 تنسيق الكائن    | كائن بسيط (object)    | كائن من نوع class              |
| 📚 التوافق مع JS   | أكثر مرونة مع JS      | موجود في JS لكن مش مثالي       |
ممكن استخدم 
const canEat = (name) => ({})
كدا لو مش هحط return 

دى ال factory function 

const canEat = (name) => ({
  eat: () => {
    console.log(`${name} can eat`);
  }
});

const canWork = (name) => ({
  work: () => {
    console.log(`${name} can work`);
  }
});

function person(name) {
  return {
    name,
    ...canEat(name),
    ...canWork(name)
  };
}

const man = person('John');

man.eat();   // Output: John can eat
man.work();  // Output: John can work
