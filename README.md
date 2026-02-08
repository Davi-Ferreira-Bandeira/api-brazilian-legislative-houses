# api-brazilian-legislative-houses

API to standardize and simplify Brazilian legislative data (Chamber & Senate) into a consistent, easy-to-consume format.

## Goals
- Unify different data sources and formats into a single API
- Simplify data access for apps, research, and public transparency

## Data sources
- Chamber: https://dadosabertos.camara.leg.br/swagger/api.html
- Senate: https://www12.senado.leg.br/dados-abertos/dados-abertos

> Note: This project is not affiliated with any government body.

## Status
🚧 Early development.

## Quickstart

### Requirements
- Python 3.10+
- Network access
- (Optional) Docker

### Run locally
```bash
git clone https://github.com/Davi-Ferreira-Bandeira/api-brazilian-legislative-houses.git
cd api-brazilian-legislative-houses
pip install -e .
run