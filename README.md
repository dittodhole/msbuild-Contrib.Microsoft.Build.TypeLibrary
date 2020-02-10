![](assets/noun_181229_cc.png)

# dotnet-Contrib.Microsoft.Build.TypeLibrary

> Create _.tlb_-files ([Type Library](https://msdn.microsoft.com/en-us/library/windows/desktop/aa366757)) upon compilation.

## Build status

[![](https://img.shields.io/appveyor/ci/dittodhole/dotnet-contrib-microsoft-build-typelibrary.svg)](https://ci.appveyor.com/project/dittodhole/dotnet-contrib-microsoft-build-typelibrary)

## Installing

### myget.org

[![](https://img.shields.io/myget/dittodhole/vpre/Contrib.Microsoft.Build.TypeLibrary.svg)](https://www.myget.org/feed/dittodhole/package/nuget/Contrib.Microsoft.Build.TypeLibrary)

```powershell
PM> Install-Package -Id Contrib.Microsoft.Build.TypeLibrary -pre --source https://www.myget.org/F/dittodhole/api/v2
```

### nuget.org

[![](https://img.shields.io/nuget/v/Contrib.Microsoft.Build.TypeLibrary.svg)](https://www.nuget.org/packages/Contrib.Microsoft.Build.TypeLibrary)

```powershell
PM> Install-Package -Id Contrib.Microsoft.Build.TypeLibrary
```

## Configuration

You can override following properties with `Directory.Build.props`:

- `ContribMicrosoftBuildTypeLibrary_Active` (default: `true` on release builds, otherwise `false`)
- `ContribMicrosoftBuildTypeLibrary_RegAsmExe`
- `ContribMicrosoftBuildTypeLibrary_RegAsmPath`
- `ContribMicrosoftBuildTypeLibrary_TlbExpExe`
- `ContribMicrosoftBuildTypeLibrary_TlbExpPath`
- `ContribMicrosoftBuildTypeLibrary_CreateTypeLibrary_BeforeTargets`
- `ContribMicrosoftBuildTypeLibrary_CreateTypeLibrary_AfterTargets` (default: `CopyFilesToOutputDirectory`)


## Developing & Building

```cmd
> git clone https://github.com/dittodhole/msbuild-Contrib.Microsoft.Build.TypeLibrary.git
> cd msbuild-Contrib.Microsoft.Build.TypeLibrary
msbuild-Contrib.Microsoft.Build.TypeLibrary> cd build
msbuild-Contrib.Microsoft.Build.TypeLibrary/build> build.bat
```

This will create the following artifacts:

- `artifacts/Contrib.Microsoft.Build.TypeLibrary.{version}.nupkg`

## License

msbuild-Contrib.Microsoft.Build.TypeLibrary is published under [WTFNMFPLv3](https://github.com/dittodhole/WTFNMFPLv3).

## Icon

[Interoperability](https://thenounproject.com/term/interoperability/181229) by [anbileru adaleru](https://thenounproject.com/pronoun) from the Noun Project.
