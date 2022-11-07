# Grid layout calls Measure on its children way too many times

This sample project demonstrates a bug in .NET MAUI with .NET 7. When using a `Grid` layout, it calls `Measure` on its children way too many times. Nesting several `Grid` layouts makes thing worse, causing the entire app to become unresponsive for several seconds. For more information see the related [.NET MAUI GitHub issue](https://github.com/dotnet/maui/issues/11140).
