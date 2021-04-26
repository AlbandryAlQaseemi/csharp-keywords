# <div dir=rtl> delegate
<div dir=rtl>delegate يشبه المؤشر على العمليات من نفس النوع وتأخذ بنفس الشروط ويستخدم خاصة لتنفيذ الـ events و  call-back methods<div>

### <div dir=rtl> مثال: <div>

<div dir=ltr>

```

public delegate int MyAction(int a, int b);
     
        public static int sum(int first, int second)
        {
            return first + second;
        }

        public static int sub(int first, int second)
        {
            return first - second;
        }
         static void Main(string[] args)
        {
            MyAction[] operations =
            {
                sum, sub
            };
            int r = 0;
            foreach (var operation in operations)
                r += operation(5, 6);
            Console.WriteLine(r);

  ```
  
  <div>
