FROM microsoft/dotnet:2.2-sdk AS build-env
WORKDIR /app
COPY . .
CMD ASPNETCORE_URLS=http://*:$PORT dotnet WebApplication_Heruko.dll
