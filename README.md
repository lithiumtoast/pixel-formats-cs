# Pixel Formats C#

Pixel formats data types in C# for computer graphics.

## Developers: How to include into your C# project

Add the following to your .csproj:

```xml
<!-- NativeTools -->
<PropertyGroup>
  <PixelFormatsSourcePath>PATH/TO/pixel-formats-cs/src</PixelFormatsSourcePath>
</PropertyGroup>
<ItemGroup>
  <Compile Include="$(PixelFormatsSourcePath)/*.cs">
    <Link>pixel-formats-cs/*.cs</Link>
  </Compile>
</ItemGroup>
```
