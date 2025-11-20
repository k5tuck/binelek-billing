# binelek-billing

Billing and webhook services

## Services Included

### 1. binah-billing (Port 8095)
Stripe subscriptions, invoice management

### 2. binah-webhooks (Port 8098)
HTTP callback delivery, retry logic, monitoring

## Quick Start

```bash
git clone https://github.com/k5tuck/binelek-billing.git
cd binelek-billing
dotnet build
dotnet test
docker-compose up
```

## Dependencies

- **binelek-shared** - Shared libraries
- .NET 8.0 SDK / Python 3.11+
- Docker

## License

MIT License - See [LICENSE](LICENSE)
