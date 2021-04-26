# <div dir=rtl> goto
<div dir=rtl>goto يستخدم لتحويل البرنامج مباشرة إلى الشرط المحدد له ومن عيوبها مقارنةً بـ for loop  فهي صعبة للقراءة. من استخداماتها الشائعة في  switch-case و للخروج من deeply nested-loops.<div>

### <div dir=rtl> مثال: <div>

<div dir=ltr>

```
  check:

            Console.WriteLine("Enter message does not contain 7: ");
            string text = Console.ReadLine();

            if (!text.Contains("7"))
            {
                goto check;
            }
  ```
  
  <div>
