# Birth Patterns Through Time

A temporal data visualization exploring how births are distributed across every minute of a 24-hour day.

The visualization transforms birth timestamps into a circular representation containing all 1,440 minutes of the day and compares birth frequency with the overall daily average.

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Temporal Data Analysis
- Polar Visualization

## Births by Minute

![Births by Minute](images/births-by-minute-circular.png)

The circular layout maps a complete 24-hour period around a polar coordinate system.

Each position corresponds to a minute of the day, while colour bands distinguish periods that fall above or below the average birth rate.

Midnight, noon, individual hours, and reference-frequency rings provide context for interpreting the distribution.

### Techniques Demonstrated

- Timestamp parsing
- Time-of-day transformation
- Aggregation across 1,440 minute intervals
- Polar coordinate visualization
- Above/below-average colour encoding
- Custom radial annotations

## Data

The analysis uses:

- `births.csv`

## Notebook

See [`analysis.ipynb`](analysis.ipynb) for the data processing and visualization implementation.
