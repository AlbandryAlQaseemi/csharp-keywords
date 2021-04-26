# <div dir=rtl> abstract
<div dir=rtl> abstract class هو class غير مكتمل  او  class خاص لا يممكننا إنشاء object منه. يستخدم بغرض الوراثة، أو لوضع بعض القواعد على الفئات أو عندما ترث. abstract methods يجب تفيذها في  abstract classes بإستخدام override.<div>

### <div dir=rtl> مثال: <div>

<div dir=ltr>

```
 public abstract class Shape
        {
            public abstract void draw();
        }
        public class Rectangle : Shape
        {
            public override void draw()
            {
                Console.WriteLine("Rectangle..");
            }
        }
  ```
  
  <div>
