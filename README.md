# OpenUtau flatpak

`nuget-sources.json` is generated with `python3 flatpak-dotnet-generator.py --dotnet 8 --freedesktop 24.08 nuget-sources.json OpenUtau/OpenUtau.csproj --runtime linux-x64 --dotnet-args -p:TreatWarningsAsErrors=false`.

See also: [flatpak's dotnet guide](https://docs.flatpak.org/en/latest/dotnet.html) and [flatpak-dotnet-generator README] (https://github.com/flatpak/flatpak-builder-tools/tree/master/dotnet)
