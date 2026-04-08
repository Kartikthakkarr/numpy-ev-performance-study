# Data Dictionary: 2025 Electric Vehicle Specifications

This document defines the features and units of measurement for the `electric_vehicles_spec_2025.csv` dataset used in the NumPy performance study.

| Column Name | Type | Unit | Description |
| :--- | :--- | :--- | :--- |
| **brand** | String | - | Manufacturer name. |
| **model** | String | - | Specific vehicle variant and trim level. |
| **top_speed_kmh** | Integer | km/h | Maximum rated velocity. |
| **battery_capacity_kWh** | Float | kWh | Total usable energy stored in the battery pack. |
| **battery_type** | String | - | Chemical composition of cells (e.g., Lithium-ion). |
| **torque_nm** | Integer | Nm | Peak rotational force of the electric motor(s). |
| **efficiency_wh_per_km** | Integer | Wh/km | Energy consumption rate (lower is more efficient). |
| **range_km** | Integer | km | Estimated driving range on a 100% charge. |
| **acceleration_0_100_s** | Float | seconds | Time taken to reach 100 km/h from a standstill. |
| **fast_charge_port** | String | - | Standard of the DC fast charging connector. |
| **drivetrain** | String | - | Configuration: AWD (All), RWD (Rear), FWD (Front). |
| **segment** | String | - | Market category (e.g., B-Compact, E-Executive). |

*Note: Missing or null values in columns like `number_of_cells` indicate data was not disclosed by the manufacturer at the time of collection.*
