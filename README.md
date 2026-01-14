# shred-landlab-prototypes

Prototype applications and pipelines combining PySHRED and Landlab for spatiotemporal forecasting and reconstruction of geophysical systems.

---

## Notebooks

### `elevation_evolution/`

| Notebook | Description |
|----------|-------------|
| `diffusion_and_fluvial_incision_2024 SHRED.ipynb` | Landlab simulation of landscape evolution using linear diffusion and detachment-limited fluvial incision. Demonstrates process competition between hillslope diffusion and channel erosion under steady-state hydrology. |
| `forecasting_fluvial_diffusion_SHRED.ipynb` | Uses SHRED to forecast elevation uplift from Landlab-generated spatiotemporal data. Compares sparse vs dense sensor placement and evaluates how well SHRED captures long-term landscape evolution patterns. |

### `sea_surface_temperature_dynamics/`

| Notebook | Description |
|----------|-------------|
| `sea_surface_temperature_forecast_SHRED.ipynb` | Forecasts weekly sea surface temperature (SST) using SHRED with the NOAA 1990-present dataset. Compares sparse vs dense sensor configurations and generates animated reconstructions of full SST fields. |

### `modified_tutorials/`

| Notebook | Description |
|----------|-------------|
| `tutorial_bunny_hill.ipynb` | Introductory PySHRED tutorial using weekly SST data. Covers `DataManager`, `SHRED` model training, and `SHREDEngine` for reconstruction — a good starting point for new users. |

---

## Dependencies

- [PySHRED](https://github.com/pyshred-dev/pyshred)
- [Landlab](https://landlab.github.io/)
- NumPy, Matplotlib, xarray