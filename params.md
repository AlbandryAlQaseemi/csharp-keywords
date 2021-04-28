# <div dir=rtl> params
<div dir=rtl> params تستخدم لتحديد parameter يأخذ عدد متغير من الـ arguments ويمكن الاستفادة منه عندما لا تكون لدينا معرفة سابقة لعدد الـarguments .<div>

### <div dir=rtl> مثال: <div>

<div dir=ltr>

```
public static void UseParam(params int[] list){

for (int i = 0; i < list.Length; i++){
Console.Write(list[i] + " ");
}
Console.WriteLine();
}

public static void UseParam2(params object[] list){

for (int i = 0; i < list.Length; i++){

Console.Write(list[i] + " ");
}
Console.WriteLine();
}

static void Main(string[] args){

UseParam(1, 2, 3, 4, 8, 5, 6);
UseParam2(1, 'a', "Albandry");
int[] myIntArray = { 5, 6, 7, 8, 9 };
UseParam(myIntArray);
}
  ```
  
  <div>
