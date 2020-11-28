FROM microsoft/dotnet:2.1-aspnetcore-runtime AS base
EXPOSE 80
WORKDIR /app
COPY ./ /app
ENTRYPOINT ["dotnet", "Equinox.Application.dll"]
