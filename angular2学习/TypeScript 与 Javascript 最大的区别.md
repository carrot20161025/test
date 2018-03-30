# TypeScript 与 Javascript 最大的区别

1. TS是强类型语言，变量是有类型的

   ```
   var1:string = 'zhangsan';    //定义一个字符串类型的变量
   var2:boolean = true;      //定义一个布尔类型的变量
   var3:number = 14;         //定义一个数字类型的变量
   var4:any = [];            //定义任何类型的变量
   var5:array = [1,2,3];     //定义数组类型的变量
   ```

2. TS中的类 class

   ```
   class Person {
      name:string = 'zhangsan';    //注意是分号
      age:number = 0;
      
      constructor(age:number) {
        this.age = age;  //构造函数是new时立即自动调用的函数
      }
      
      sayName {
        console.log(this.name)
      }
   }

   var6:Person = new Person(70);
   ```

3. class中带有属性保护和私有属性

   ```
   public  -  公共属性和方法，都能访问
   protected - 受保护的属性
   private - 私有属性，不能在实例中直接调用
   ```

4. 箭头函数

   ```
   () => {}
   ```

   ​