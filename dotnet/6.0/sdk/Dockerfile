# escape=`

FROM mcr.microsoft.com/dotnet/sdk:6.0 AS build

ARG PAT
ARG FEED

RUN wget -qO- https://aka.ms/install-artifacts-credprovider.sh | bash

RUN dotnet nuget add source "${FEED}"

ENV VSS_NUGET_EXTERNAL_FEED_ENDPOINTS="{`"endpointCredentials`": [{`"endpoint`":`"${FEED}`", `"username`":`"docker`", `"password`":`"${PAT}`"}]}"