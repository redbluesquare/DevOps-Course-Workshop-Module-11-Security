FROM mcr.microsoft.com/dotnet/sdk:6.0

WORKDIR /weatherforecast

COPY . ./
RUN dotnet build

ENTRYPOINT [ "dotnet", "run", "--urls", "http://0.0.0.0:5000" ]
