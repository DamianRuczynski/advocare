# Advocare monorepo (Nx)

## wymagania

- Node 20 + pnpm
- Docker (opcjonalnie na później)

## szybki start

pnpm install
pnpm nx serve api-gateway
pnpm nx serve web

## struktura

- apps/web (Angular)
- apps/admin (Angular)
- apps/api-gateway (NestJS)
- apps/svc-search (NestJS)
- apps/svc-vector (NestJS)
- apps/ai-service (Python FastAPI)
- libs/api-types, libs/shared-utils
