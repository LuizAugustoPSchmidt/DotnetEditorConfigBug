Before running `dotnet format`:
```
try
{
  System.Console.WriteLine("Hello World");
}
catch {};
```

After:
```
try
{
  System.Console.WriteLine("Hello World");
}
catch { };
```
