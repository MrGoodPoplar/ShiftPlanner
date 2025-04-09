FROM mcr.microsoft.com/dotnet/sdk:9.0

WORKDIR /app

EXPOSE 8080
EXPOSE 8081

ENTRYPOINT ["dotnet", "watch", "run", "--urls", "http://0.0.0.0:8080"]