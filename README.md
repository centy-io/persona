# @centy/persona

Persona CLI by [Centy](https://github.com/centy-io) — manage user personas and stories from the command line.

## Prerequisites

`@centy/persona` communicates with the **centy daemon** over **gRPC**.

- The [centy daemon](https://github.com/centy-io/centy-daemon) must be installed and running locally (default: `127.0.0.1:50051`)
- See the [centy-daemon repo](https://github.com/centy-io/centy-daemon) for installation instructions
- `persona init` will fail with a connection error if the daemon is not running

## Installation

```sh
# Run without installing
npx @centy/persona init

# Install globally
npm install -g @centy/persona
```

## Usage

```sh
persona init
```

## License

MIT
