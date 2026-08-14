# opencode

An open-source toolkit for building reliable, observable code pipelines.

## Features

- Declarative pipeline definitions
- Built-in health checks and retries
- Structured logging
- Pluggable backends

## Quick Start

```bash
pip install opencode
opencode init my-pipeline
```

## Example

```yaml
pipeline:
  name: example
  steps:
    - run: echo "hello"
      retries: 2
```

## Documentation

See the [docs](docs/) for full API reference.

## Contributing

Feel free to open issues or PRs. We welcome community improvements.

## License

MIT