# Data Analysis for CubeSat Missions

## Tools Used
- Python (pandas, matplotlib)
- Jupyter Notebooks
- SatNOGS database exports

## Example: Decoding and Plotting Telemetry
```python
import pandas as pd
import matplotlib.pyplot as plt

df = pd.read_csv('lucia_telemetry.csv')
plt.plot(df['timestamp'], df['battery_voltage'])
plt.xlabel('Time')
plt.ylabel('Battery Voltage (V)')
plt.title('LUCIA Battery Voltage Over Time')
plt.show()
```

## References
- [SatNOGS DB](https://db.satnogs.org/)
- [CubeSat Telemetry Analysis](https://digitalcommons.usu.edu/smallsat/2021/all2021/60/)
