## Convert Neonatal Growth Curve Spreadsheets to JSON
This Python notebook provides a script to convert Dr. Fou-Sheng Chou's neonatal growth curve data, which is stored in spreadsheets, into JSON files sorted by gestational age and sex. This data is used in the NicuGrowth application. The notebook utilizes the Pandas library for data manipulation and the Openpyxl library for handling Excel files.

## Features
- Converts neonatal growth curve data from spreadsheets to JSON files.
- Sorts the data by gestational age group and sex for easier analysis.
- Performs data cleaning and transformation to remove empty fields and adjust values if necessary.
- Handles both individual growth curve sheets and sample workbook curves.

## Usage
1. Open the notebook file growth_curve_sheets_2_json.ipynb in a Jupyter Notebook environment or any compatible notebook viewer.
2. Run the notebook cells sequentially to convert the neonatal growth curve spreadsheets to JSON files.
3. The converted JSON files will be saved in the same directory as the notebook, organized by gestational age group and sex.

## Acknowledgements
The conversion script in this repository is based on the research and data provided by Dr. Fou-Sheng Chou. We acknowledge his contribution and appreciate the opportunity to work with this valuable dataset.