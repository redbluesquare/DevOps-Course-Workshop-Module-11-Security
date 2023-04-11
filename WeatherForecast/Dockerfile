FROM mcr.microsoft.com/dotnet/sdk:6.0

WORKDIR /workshop

COPY . ./

WORKDIR /workshop/WeatherForecast
RUN dotnet build

ENTRYPOINT dotnet run
