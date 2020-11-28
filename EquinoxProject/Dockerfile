FROM mcr.microsoft.com/dotnet/core/aspnet:3.1 AS base
EXPOSE 80
WORKDIR /app
COPY ./ /app
ENTRYPOINT ["dotnet", "Equinox.Application.dll"]
