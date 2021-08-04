# Examle Nuget Packages dotnettemplates

step 1 -> Create Project using dotnet new {shortname}
step 2 -> in Project Directory -> Create folder [.template.config] -> in .template.config create file [template.json] and then add code hear
step 3 -> in root directory project create file [.nuspec] and then past code hear
step 4 -> download nuget.exe from https://www.nuget.org/downloads 
step 4 -> use command -> D:\{path of nuget.exe}\nuget.exe pack D:\{path of .nuspec}\Codezonelive.Templates.nuspec -NoDefaultExcludes -OutputDirectory D:\Temp
step 5 -> use command -> dotnet new --install D:\Temp\Codezonelive.Templates.1.0.4.nupkg
step 6 -> check installation dotnet new --list if found template of you that work

--- upload to nuget packages ---
step 1 goto https://www.nuget.org/packages -> Sign In -> select Upload -> Browse Codezonelive.Templates.1.0.4.nupkg



--- End ---
