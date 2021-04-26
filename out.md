# <div dir=rtl> out
<div dir=rtl>تستخدم لتمرير arguments إلى الدوال كنوع مرجعي. يتم استخدامها بشكل عام في الدوال لإرجاع قيم متعددة.<div>

### <div dir=rtl> مثال: <div>

<div dir=ltr>

```
  public static void sum(out int a, out int b)
        {
            a = 2;
            b = 3;
            a += b;
        }

        static void Main(string[] args)
        {
            int i, j;
            sum(out i, out j);

            Console.WriteLine(i);
        }
  ```
  
  <div>
