
# <div dir=rtl> public
<div dir=rtl> تستخدم للإعلان عن إمكانية الوصول الكامل للكلاسات والدوال ورؤية كاملة لجميع أنواع المتغيرات والدوال.<div>

### <div dir=rtl> مثال: <div>

<div dir=ltr>

```
 public class Student
        {
            public static int count = 0;
            public int id;
            public string name;
            public int age;
            
       public Student(int id, string name, int age)
            {
                this.id = id;
                this.name = name;
                this.age = age;
            }
       public void printInfo()
            {
                string message = "My name is: " + this.name + " my age: " + this.age + " my id: " + this.id;
                Console.WriteLine(message);
            }
        }
           static void Main(string[] args)
            {
          Student me = new Student(1, "Albandry", 24);
           me.printInfo();
            }

  ```
  
  <div>
