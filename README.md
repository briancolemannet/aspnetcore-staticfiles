# aspnetcore-staticfiles

## Why

I have always loved the idea of getting a web server up with minimal effort so that I can fiddle with frameworks. I am an
ASP.NET developer and haven't had this option. I really loved other frameworks such as [nodejs](https://nodejs.org "Node.js Homepage")
because you can quickly and from the command line, create a static web server that is fast an responsive. Although the current version
of AspNetCore (RC2 is the current version) is not as feature rich as the NPM echosystem, I think it is a giant step in the right
direction, IMHO.

## What

This sample code is setup to be ran from the command line. It also uses kestral, not IIS (Express) for hosting. It wouldn't take much to
add support for IIS(Express) but I wanted to be able to clone it from the command prompt (terminal for you OSX/linus peeps) and then, with
a few commands, have an http server playground to mess with.

## How

Assuming you have [.Net Core](https://www.microsoft.com/net/download#core) installed already, just type `dotnet restore` (restores the
NuGet packages that are dependencies) and then `dotnet run` which starts the server. By default it will listen to port 5000.

## Help

I need to mention that I used [Bobby Johnson's](https://stackoverflow.com/cv/notmyself) [blog post](http://iamnotmyself.com/blog/2016/05/19/building-a-static-file-server-in-asp-net-core-rc2-with-the-cli "Building a Static File Server in ASP.NET Core RC2 with the CLI")
as a reference when I got stuck a few times in the process.

## Hype

I am very excited to see where [DotNetCore](https://github.com/dotnet/core) and [AspNetCore](https://github.com/aspnet/Home) go in the future!

## Who

Brian