# <div dir=rtl> ref
<div dir=rtl>تستخدم  ref لتمرير أو إرجاع مراجع القيم من وإلى الدوال. يعني هذا بشكل أساسي أن أي تغيير يتم إجراؤه على القيمة التي تم تمريرها عن طريق المرجع سيعكس هذا التغيير نظرًا لأنك تقوم بتعديل القيمة في العنوان وليس القيمة فقط.<div>

### <div dir=rtl> مثال: <div>

<div dir=ltr>

```
			int x = 4;

            add(ref x); 

            Console.WriteLine(x);

            static void add(ref int num)
            {
                num += 1; ;
                Console.WriteLine(num);
            }
  ```
  
  <div>
