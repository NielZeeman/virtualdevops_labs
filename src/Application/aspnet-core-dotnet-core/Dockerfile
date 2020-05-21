FROM mcr.microsoft.com/dotnet/core/sdk:3.1-buster AS base
ENV ASPNETCORE_URLS=http://+:80
EXPOSE 80

WORKDIR /app

# Copy the published web app
COPY . /app

# Run command
ENTRYPOINT ["dotnet", "aspnet-core-dotnet-core.dll"]
