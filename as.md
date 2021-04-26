# <div dir=rtl> as
<div dir=rtl> في حالة تحويل الـobject من object(type) إلى object(type) من نوع آخر قد يحصل InvalidCastException, لذلك يجب استخدام as لحل مشكلة التحويل.  وأيضا يمكن استخدامه للتحويل بين الكائنيات المتوافقة بإرجاع قيمة متوافقة مع النوع أو تستخدم للتحويل بين قيم Nullable بإرجاع قيمة فارغة عندما لا يتم التحويل.<div>

### <div dir=rtl> مثال: <div>

<div dir=ltr>

```
        string str1 = "Csharp";
        object obj1 = str1;

        string str2 = obj1 as string;
 
        if(str2 != null)
        {
            Console.WriteLine("Successfully Cast");
        }
        List<string> mylist = obj1 as List<string>;
        if(mylist != null)
        {
            Console.WriteLine("Successfully Cast");
        }
        else
        {
            Console.WriteLine("Not Successfull");
        }
  ```
  
  <div>
