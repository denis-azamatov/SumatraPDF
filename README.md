# SumatraPDF nuget wrapper

"SumatraPDF.exe" does not appear in Solution Explorer, but it is copied to the output folder from the package source folder when the build process.

NuGet package restoring ready, and no need to commit "SumatraPDF.exe" binary into source code control repository.

## How to build and publish

```
nuget pack
```

```
dotnet nuget push [package name].nupkg -s [destination]
```