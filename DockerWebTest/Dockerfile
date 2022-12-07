FROM mcr.microsoft.com/dotnet/core/aspnet:3.0-buster-slim
EXPOSE 80
EXPOSE 443
WORKDIR /app
COPY /bin/Release/netcoreapp3.0/publish /app
ENTRYPOINT ["dotnet", "DockerWebTest.dll"]
