# biotech-practice

Proyecto de práctica de biotech en Python.

## Requisitos

- Python 3.12 o superior

## Instalación

```bash
python -m venv .venv
# Windows (PowerShell)
.venv\Scripts\Activate.ps1
# macOS / Linux
source .venv/bin/activate

pip install -e ".[dev]"
```

## Uso

```bash
pytest          # correr tests
ruff check .    # lint
ruff format .   # formatear
```

## Estructura

```
biotech/      # código del paquete
tests/        # tests con pytest
```
