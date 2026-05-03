# Schema

## `index.yaml`

Top-level key:
- `models`: array of model entries

Each model entry in `index.yaml`:
- `name`: string
- `slug`: string
- `github`: string
- `status`: string

## `models/<slug>/model.yaml`

Required keys:
- `name`: string
- `github`: string
- `status`: string
- `deployment`: map
  - `method`: string
  - `config_path`: string
