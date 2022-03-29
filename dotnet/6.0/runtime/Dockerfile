FROM mcr.microsoft.com/dotnet/runtime:6.0-alpine

RUN addgroup -g 1000 dotnet &&\
  adduser -u 1000 -G dotnet -s /bin/sh -D dotnet
USER dotnet
