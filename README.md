# sfml-nuget_builder
Create NuGet's package for SFML.

# Prerequisite

- The CoApp toolset (http://coapp.org/)

# How to

You just have to run the sfml-nuget.ps1 script in a PowerShell instance.
It will download each needed files and output nupkg files in the "repository" folder.

# Customization

You can customize packages by changing this params:
- `$pkg_prefix` to change packages' names **(Don't remove the reference to the SFML)**
- `$pkg_owner` to change packages' owner
- `pkg_tags` to customize tags
- `$pkg_clear_sources` to keep or delete source files

### Optional :
You can modify some variables to select the SFML version, generate only specific modules, etc...
**You should know what your are changing!**
