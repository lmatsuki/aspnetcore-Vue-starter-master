# Asp.NETCore 2.1 Vue 2 Starter - by [DevHelp.Online](http://www.DevHelp.Online)

This repo contains an ASP.NET Core + Vue.js 2 starter template (VS2017 or command line). The template is based
on the [original starter templates](https://blogs.msdn.microsoft.com/webdev/2017/02/14/building-single-page-applications-on-asp-net-core-with-javascriptservices/) (Angular, Knockout, React, Aurelia), which can be found [here](https://github.com/aspnet/JavaScriptServices/tree/dev/templates)

_Looking for ASP.NET Core & Angular 6.x+ Universal starter? [click here](https://github.com/MarkPieszak/aspnetcore-angular2-universal)_
 
---

# Table of Contents

* [Features](#features)
* [Prerequisites](#prerequisites)
* [Installation](#installation)
* [Getting Started](#getting-started)
* [Extras](#extras)
* [Special Thanks](#special-thanks)
* [License](#license)
* [Social Media](#follow-me-online)
* [VueJS & ASP.NET Consulting & training](#Training)

# Features

- **ASP.NET Core 2.1**
  - Web API
- **VueJS 2**
  - Vuex (State Store)
- **Webpack**
  - HMR (Hot Module Replacement/Reloading)
- **Bootstrap 4**

# Prerequisites:
 * [.Net Core 2.1](https://www.microsoft.com/net/download/windows)
 * [NodeJS](https://nodejs.org/) >= 8.9.4
 * [VSCode](https://code.visualstudio.com/) (ideally), or VS2017

# Installation:
 * Install the template from nuget: `dotnet new -i aspnetcore-vuejs`
 
# Getting Started:
 * Create folder from template: `dotnet new vuejs` ([Official documentation](https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-new?tabs=netcore2x))
   * This will automatically run `dotnet restore` unless you install with `dotnet new vuejs --skipRestore`
 * Restore Node dependencies by running `npm install`

## Start the application:
You have two choices when it come at how your preffer to run it. You can either use the command line or the build-in run command.

### 1. Using the command line
Run the application using `dotnet run` or `npm run dev`
- note `dotnet run` should be run in `Development` environment for hot reloading. This setting can be set either within the command line or via the `launchSettings.json` available in the `Properties` folder.
 
### 2. Using the built-in run command
Run the application in VSCode or Visual Studio 2017 by hitting `F5`.

## View your application running
Browse to [http://localhost:5000](http://localhost:5000)

# Recommended plugin for debugging VueJS

- Get Chrome DevTools for VueJS [here](https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd)
