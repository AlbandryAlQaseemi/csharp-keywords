# <div dir=rtl> base
<div dir=rtl>base تستخدم للوصول إلى fields, classes, methods and constructors  لـ base class من الـ class المشتق او الموروث من المفضل أن يكون للـ base and derived classes نفس الحقول. إذا لم تحدد الفئة المشتقة نفس الحقل ، فلا داعي لاستخدام base. يمكن الوصول إلى base class مباشرةً بواسطة derived class. <div>

### <div dir=rtl> مثال: <div>

<div dir=ltr>

```
    public MessageDecorator(string message)
                {
                    this.message = message;
                    Console.WriteLine("Base has initilized");
                }

                public virtual string decorate()
                {
                    return "[:" + this.message + ":]";
                }
            public class EasyMessageDecorater : MessageDecorator
            {
                public EasyMessageDecorater(string message) : base(message)
                {
                    Console.WriteLine("Subclass has initilized");
                }
                public override string decorate()
                {
                    return "***" + this.message + "***";
                }
            }
  ```
  
  <div>
