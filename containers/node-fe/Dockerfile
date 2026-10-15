ARG NODE_FE_VERSION=22
FROM node:${NODE_FE_VERSION}-alpine

# git: npm deps from git urls + codegen tooling; bash: SDK convention for shells
RUN apk add --no-cache git bash

WORKDIR /app

# Keep the container alive as a dev/CI-like runner; commands run via `docker compose exec`
CMD ["sleep", "infinity"]
