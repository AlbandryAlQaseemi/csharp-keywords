# <div dir=rtl> enum
<div dir=rtl>  enum هو class يستخدم لتمثيل مجموعة من الثوابت غير قابلة للتغيير وتكون للقراءة فقط. <div>

### <div dir=rtl> مثال: <div>

<div dir=ltr>

```
    class Program{
    
enum days {
Sunday,
Monday,
Tuesday,
Wednsday,
Thursday,
Friday };

static void Main(string[] args){

int WeekDayStart = (int)days.Sunday;
int weekDayEnd = (int) days.Thursday;
days Sunday1 = (days)WeekDayStart;

Console.WriteLine("The day is: " + Sunday1);
Console.WriteLine("Sunday: {0}", WeekDayStart);
Console.WriteLine("Thursday: {0} " , weekDayEnd);
} 

  ```
  
  <div>
