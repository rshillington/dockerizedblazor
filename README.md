A simple repo to illustrate creating a [Blazor WASM app](https://devblogs.microsoft.com/aspnet/blazor-webassembly-3-2-0-release-candidate-now-available/) hosted in a docker container.

```
docker build -t blazorapp:latest .
docker run -d --rm -p 80:80 --name blazorapp blazorapp:latest
open http://localhost:5000
```
Season to taste.