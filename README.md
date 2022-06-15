# Dapr Middleware Rate Limit with Net6

Test with rate limit:

dapr run --app-id apione --config config.yaml --components-path ./components --app-port 5000 --dapr-http-port 3500 -- dotnet run --project apione/apione.csproj

Test without rate limit:

dapr run --app-id apione --components-path ./components --app-port 5000 --dapr-http-port 3500 -- dotnet run --project apione/apione.csproj