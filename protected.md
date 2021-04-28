
# <div dir=rtl> protected
<div dir=rtl> تستخدم فقط في نفس الكلاس والكلاسات الموروثة ولكن لايمكن استدعاؤها في main class.<div>

### <div dir=rtl> مثال: <div>

<div dir=ltr>

```
              public class MyData
            {
                protected int second;
                
                public MyData()
                {
                    this.second = 2;
                    this.secondPrint();
                }
                protected void secondPrint() { }
            }

            public class YourData : MyData
            {

                public YourData()
                {
                    this.second = 2;   
                }
                
            }  
  ```
  
  <div>
