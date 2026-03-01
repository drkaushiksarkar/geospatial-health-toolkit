# Geospatial Health Toolkit

Geospatial analysis toolkit for health facility mapping, service area modeling, spatial clustering, and epidemiological hotspot detection.

## Architecture

```
geospatial-health-toolkit/
  src/           # Core modules
  tests/         # Unit and integration tests
  config/        # Configuration files
  docs/          # Documentation
```

## Modules

- **facility_mapper**: Core facility mapper functionality
- **catchment_analyzer**: Core catchment analyzer functionality
- **spatial_cluster**: Core spatial cluster functionality
- **distance_matrix**: Core distance matrix functionality
- **hotspot_detector**: Core hotspot detector functionality

## Quick Start

```bash
pip install -r requirements.txt
python -m geospatial_health_toolkit.main
```

## Testing

```bash
pytest tests/ -v
```

## License

MIT License - see LICENSE for details.
