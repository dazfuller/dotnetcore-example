# .NET Core - OSX Example

This is an implementation of the .NET Core OSX example as presented
on the [.NET Core Tutorial](https://docs.microsoft.com/dotnet/articles/core/tutorials/using-on-macos).

I put this together as there are a couple of things which get a little confusing in the documentation if you read the Windows version and then the OSX and I wanted a reference.

# Compiling and running

From the root directory run the following command:

```bash
dotnet restore
```

This will restore all of the solution dependencies. You can then execute the following from the `/src/app` directory.

```bash
dotnet run
```

This will execute the application. Alternatively execute the following from the `/test/test-library` to test the library.

```bash
dotnet test
```