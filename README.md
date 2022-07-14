![Logo of DisCatSharpNext](https://github.com/DSharpPlus/DSharpPlus/raw/master/logo/dsharp+_smaller.png)

# DisCatSharpNext
The NEXT level of DisCatSharp, an unforeseen improvement, You'll love it. Try it. 

[![Nightly Build Status](https://github.com/DSharpPlus/DSharpPlus/actions/workflows/publish_nightly.yml/badge.svg?branch=master)](https://github.com/DSharpPlus/DSharpPlus/actions/workflows/publish_nightly.yml)
[![Discord Server](https://img.shields.io/discord/379378609942560770.svg?label=discord)](https://discord.gg/dsharpplus)
[![NuGet](https://img.shields.io/nuget/v/DSharpPlus.svg)](https://nuget.org/packages/DSharpPlus)
[![NuGet Latest Nightly/Prerelease](https://img.shields.io/nuget/vpre/DSharpPlus.svg)](https://nuget.org/packages/DSharpPlus)

# Installing
You can install the library from following sources:

1. All Nightly versions are available on [Nuget](https://www.nuget.org/packages/DSharpPlus/) as a pre-release. These are cutting-edge versions automatically built from the latest commit in the `master` branch in this repository, and as such always contains the latest changes. If you want to use the latest features on Discord, you should use the nightlies.

   Despite the nature of pre-release software, all changes to the library are held under a level of scrutiny; for this library, unstable does not mean bad quality, rather it means that the API can be subject to change without prior notice (to ease rapid iteration) and that consumers of the library should always remain on the latest version available (to immediately get the latest fixes and improvements). You will usually want to use this version.

2. The latest stable release is always available on [NuGet](https://nuget.org/packages/DSharpPlus). Stable versions are released less often, but are guaranteed to not receive any breaking API changes without a major version bump.

   Critical bugfixes in the nightly releases will usually be backported to the latest major stable release, but only after they have passed our soak tests. Additionally, some smaller fixes may be infrastructurally impossible or very difficult to backport without "breaking everything", and as such they will remain only in the nightly release until the next major release. You should evaluate whether or not this version suits your specific needs.

3. The library can be directly referenced from your csproj file. Cloning the repository and referencing the library is as easy as:
    ```
    git clone https://github.com/DSharpPlus/DSharpPlus.git DSharpPlus-Repo
    ```
    Edit MyProject.csproj and add the following line:
    ```xml
    <ProjectReference Include="../DSharpPlus-Repo/DSharpPlus/DSharpPlus.csproj" />
    ```
    This belongs in the ItemGroup tag with the rest of your dependencies. The library should not be in the same directory or subdirectory as your project. This method should only be used if you're making local changes to the library.

# Documentation
The documentation for the latest stable version is available at [dsharpplus.github.io](https://dsharpplus.github.io/).