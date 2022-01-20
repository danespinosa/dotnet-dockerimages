# escape=`

FROM mcr.microsoft.com/dotnet/aspnet:6.0.1-nanoserver-ltsc2022 as build
WORKDIR /app
COPY . .
EXPOSE 80
EXPOSE 443
ENTRYPOINT ["dotnet", "WebApplication2.dll"]
