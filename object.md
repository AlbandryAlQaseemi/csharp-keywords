# <div dir=rtl> object
<div dir=rtl>object يكتب من الـclass وتكون طريقة كتابته بدايةً بإسم الـclass متبوعًا بإسم الـobject ويمكننا انشاء اكثر من object لنفس الـclass .<div>

### <div dir=rtl> مثال: <div>

<div dir=ltr>

```
   class Car
        {
            string r = "red";
            string b = "blue";
            static void Main(string[] args)
            {
                Car myObj1 = new Car();
                Car myObj2 = new Car();

             Console.WriteLine(myObj1.r);
             Console.WriteLine(myObj2.b);
            }
        }
  ```
  
  <div>
