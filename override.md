
# <div dir=rtl> override
<div dir=rtl>  تستخدم لتعديل او تحديث abstract او virtual implementation للدوال او الخصائص الموروثة .<div>

### <div dir=rtl> مثال: <div>

<div dir=ltr>

```
       public class MessageDecorator
            {
                public string message;


       public MessageDecorator(string message)
        {
         this.message = message;
         Console.WriteLine("Base has initilized");
         }
        public virtual string decorate()
         {
           return "[:" + this.message + ":]";
         }

         } 
        public class EasyMessageDecorater : MessageDecorator
            {
                public EasyMessageDecorater(string message) : base(message)
                {
                    Console.WriteLine("Subclass has initilized");
                }
                public override string decorate()
                {
                    return "**" + this.message + "**";
                }
            }
  ```
  
  <div>
