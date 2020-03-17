## CHAPTER 03

# Getting Started

Getting started with IndyMicro.NET involves building and installing the "dotnet new" templates which are then used to generate your own projects.

### Install the pre-requisites

Visual Studio 2019 with [.NET Core 3.1](https://dotnet.microsoft.com/download/dotnet-core/3.1)

(on Linux, it should be possible to run all of the build commands without VS but this has not been tested yet.)

### Clone the repository

```
git clone https://github.com/westonsoftware/IndyMicro.NET
```

### Build the project templates

Open the ***IndyMicro.sln*** file in Visual Studio and press **F6** to build all.

(each project can also be built from the command line.)

```
dotnet build .\IndyMicro.Host\IndyMicro.Host.csproj
```

You should now be able to F5 run your Host project to see server output in the console.  

## Install the project templates

```
dotnet new -i <PATH_TO_YOUR_REPO>\IndyMicro.Host
dotnet new -i <PATH_TO_YOUR_REPO>\IndyMicro.Infrastructure
dotnet new -i <PATH_TO_YOUR_REPO>\IndyMicro.Context
dotnet new -i <PATH_TO_YOUR_REPO>\IndyMicro.Gateway
dotnet new -i <PATH_TO_YOUR_REPO>\IndyMicro.Module.Sample
dotnet new indymicro --list
```

The final command will list all of the dotnet templates that were installed ...

```
Templates                     Short Name                    
------------------------------------------------------------
IndyMicro Gateway             indymicro-gateway             
IndyMicro Host                indymicro-host                
IndyMicro Infrastructure      indymicro-infrastructure      
IndyMicro Module              indymicro-module    
IndyMicro Context             indymicro-context
```

### Build the sample admin web client

Our sample client application is built using the [Quasar Framework](https://quasar.dev/).

Follow the [installation steps here](https://quasar.dev/quasar-cli/installation), this includes Node and Npm. 

Then you can build the client like this:

```
cd IndyMicro.Admin
npm install
yarn install
quasar build
```

You should now be able to run your web project on *localhost*  like this:

```
quasar dev
```

  

[< Back](index.md)





