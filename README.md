Run a boxstarter script that installs a memory scanner, debugger and firefox.

# How to use
Run the following two scripts in powershell:

. { iwr -useb https://boxstarter.org/bootstrapper.ps1 } | iex; Get-Boxstarter -Force

Install-BoxstarterPackage -PackageName https://raw.githubusercontent.com/Reevoke1/vmsetup/main/vmsetup.txt -DisableReboots
