# Csharp-get-and-display-time
C#获取并显示当前时间的程序
using System;：这是一个命名空间的引用，包含了许多常用的类型和方法，例如DateTime和Console。
class Program：定义了一个名为Program的类，作为程序的入口点。
static void Main()：这是程序的主方法，程序从这里开始执行。
DateTime currentTime = DateTime.Now;：创建一个DateTime对象并将其赋值给currentTime变量。DateTime.Now返回当前的日期和时间。
Console.WriteLine("Current time: " + currentTime);：使用Console.WriteLine方法将带有当前时间的字符串打印输出到控制台。
