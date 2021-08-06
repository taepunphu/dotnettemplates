# Example Nuget Packages dotnettemplates

step 1 -> Create Project using dotnet new {shortname} <br />
step 2 -> in Project Directory -> Create folder [.template.config] -> in .template.config create file [template.json] and then add code hear<br />
step 3 -> in root directory project create file [.nuspec] and then past code hear<br />
step 4 -> download nuget.exe from https://www.nuget.org/downloads <br />
step 4 -> use command -> D:\{path of nuget.exe}\nuget.exe pack D:\{path of .nuspec}\Codezonelive.Templates.nuspec -NoDefaultExcludes -OutputDirectory D:\Temp<br />
step 5 -> use command -> dotnet new --install D:\Temp\Codezonelive.Templates.1.0.4.nupkg<br />
step 6 -> check installation dotnet new --list if found template of you that work<br />

--- upload to nuget packages ---<br />
step 1 goto https://www.nuget.org/packages -> Sign In -> select Upload -> Browse Codezonelive.Templates.1.0.4.nupkg<br />



--- End ---<br />
