# WebmFun 
#### Create weird webm files that will confuse discord's player! :D
A simple single-file C# script that edits bytes of webm files with the needed duration that will confuse discord.

**WARNING:** this program only edits the bytes of the file, it won't copy the content of the file to fit the duration.
## Idea
I was inspired by infinite discord videos (again), so i wanted to automate that.
## Build
To run this script, you'll need to build it.
It uses .NET Core, which you can install here: https://dotnet.microsoft.com/download

1. Clone the repository: `git clone https://github.com/NedoProgrammer/WebmFun.git`

2. `cd` into the project directory: `cd WebmFun`

3. Build the project: `dotnet build --configuration Release`  

When finished, you'll find the executable in `/bin/Release/netcoreapp3.1/`

If you downloaded the Linux Prebuild, you need to `chmod` the executable:

1. `cd` into the project directory: `cd WebmFun`

2. `cd` into the prebuild directory: `cd LinuxPrebuild`

3. `chmod` the executable: `chmod +x WebmFun`

4. Run! `./WebmFun` 
## Dependencies

Hexify for editing the hex of the webm file: https://github.com/lowleveldesign/hexify
## Usage
Simply run the executable, and follow the on-screen instructions :)
