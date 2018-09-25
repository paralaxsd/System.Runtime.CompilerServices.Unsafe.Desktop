# System.Runtime.CompilerServices.Unsafe (Desktop variant)

This repository provides a CLR 4 compatible version of [System.Runtime.CompilerServices.Unsafe](https://github.com/dotnet/corefx/tree/master/src/System.Runtime.CompilerServices.Unsafe).

It is based on the work from [DotNetCross/Memory.Unsafe](https://github.com/DotNetCross/Memory.Unsafe) (basic setup) and [dotnet/corefx](https://github.com/dotnet/corefx/tree/master/src/System.Runtime.CompilerServices.Unsafe) (most of the actual IL).

## Why might this be useful?
If you need the functionality of the `Unsafe` class in your Desktop application and you don't want to pull in a myriad of assemblies drawn in via the original netcoreapp/netstandard dependency this project might be for you!

## How recent is this variant of Unsafe?
The original il file was taken from [this commit](https://github.com/dotnet/corefx/commit/64c6d9fe5409be14bdc3609d73ffb3fea1f35797).
