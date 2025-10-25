# DomotiPy

DomotiPy is a modular Python framework for home automation. It uses a plugin-based architecture for sensor readout, control routines, database backends and future extensions.

## Philosophy

DomotiPy is built around the idea that home automation should be:
- **Modular**: Each component is a plugin — from sensor logic to database backends.
- **Transparent**: Clear interfaces, structured behavior, and fallback logic.
- **Open**: Licensed under GPLv3 to ensure freedom, collaboration, and protection against commercial lock-in.

## Structure

- `core/`: base interfaces and plugin manager
- `plugins/`: concrete plugin implementations
- `config/`: YAML configuration files
- `docs/`: project documentation
- `tests/`: unit tests

## License

This project is licensed under the GNU General Public License v3.0. See the [LICENSE](./LICENSE) file for details.

## Contributions

Pull requests are welcome. See [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines on plugin structure, logging style, and test coverage.

## Inspiration

DomotiPy is conceptually inspired by Domoticz, but built from scratch in Python with a focus on modularity and extensibility.

## Status

This project is in early development. Expect rapid iteration, playful logic, and evolving documentation.
