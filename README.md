# ASP.NET.Day9

# Задание 1.
Рассмотреть специфику работы со значимыми типами на примере пользовательской структуры 
```csharp
public struct Point2D
{
	public int X; 
	public int Y;
}
```
используя SOS.dll (https://msdn.microsoft.com/en-us/library/bb190764%28v=vs.110%29.aspx, https://dpaoliello.wordpress.com/2012/02/05/getting-the-disassembly-and-il-for-a-jittedngened-net-method-using-windbg-and-sos-dll/), WinDbg и Disassembly (VS) в контексте вызова экземплярных не виртуальных, виртуальных методов, унаследованных от Object (переопределенных и не переопределенных), а также методов интерфейсов (например, IComparable), а также таблицы методов, структуры EEClass и т.д.

Вам помогут статья https://msdn.microsoft.com/ru-ru/library/dd335945.aspx и глава 3 *(TYPE INTERNALS)* книги **.NET Performance**.

Результат оформить в виде скриншотов и коротких выводов. 
