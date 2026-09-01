# OpenCode

OpenCode is an open-source development platform designed for collaborative coding, automated task execution, and infrastructure observability.

## Features

- **Fast Execution**: Built with low latency and high concurrency in mind.
- **Reliable Workflows**: Built-in retry mechanisms and health monitoring.
- **Integrations**: Supports major CI/CD pipelines and alerting systems.

## Quick Start

```bash
# Clone the repository
git clone https://github.com/anomalyco/opencode.git
cd opencode

# Start the service
docker-compose up -d
```

## Configuration

Set environment variables in `.env`:

```env
PORT=8080
LOG_LEVEL=info
METRICS_ENABLED=true
HEALTH_CHECK_INTERVAL=30s
```

## Health Checks & Monitoring

OpenCode exposes an HTTP health endpoint at `/health` returning `200 OK` with JSON status when ready to serve traffic, suitable for load balancers and orchestrator liveness probes.

## License

MIT