FROM mcr.microsoft.com/dotnet/sdk:8.0 AS build

WORKDIR /src

COPY . .

RUN dotnet restore

CMD dotnet test "./DatabaseProject.Test/DatabaseProject.Test.csproj"
