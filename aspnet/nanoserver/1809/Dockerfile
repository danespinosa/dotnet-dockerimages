# escape=`

FROM mcr.microsoft.com/dotnet/aspnet:6.0-nanoserver-1809 as build
WORKDIR /app
COPY . .
EXPOSE 80
EXPOSE 443
ENTRYPOINT ["dotnet", "WebApplication2.dll"]
