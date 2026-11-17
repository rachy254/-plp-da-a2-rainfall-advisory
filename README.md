# County Rainfall and Planting Advisory

## Project Summary
This project cleans raw meteorological station data, performs vectorized NumPy rainfall analysis across five Kenyan counties (Nairobi, Nakuru, Kisumu, Mombasa, and Machakos), and generates an actionable agricultural planting advisory and summary CSV report.

## How to Run the Notebook
1. Open `rainfall_analysis.ipynb` in Google Colab or Jupyter Notebook.
2. Ensure `numpy` is installed.
3. Restart the kernel and run all cells from top to bottom (`Kernel > Restart & Run All`).
4. Verify that `rainfall_summary.csv` is generated successfully in the working directory.

## Planting Advisory
* Farmers should align crop sowing with peak two-month rainfall windows to optimize soil moisture during germination.
* Monitor dry-month counts (< 50 mm) to schedule supplementary irrigation or choose drought-tolerant varieties.
* Extension officers must account for statistical data-quality imputations when planning localized seed distribution in Machakos.
