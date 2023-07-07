# WranglingRealEstateData
In this project, I wrangled suburban real estate housing data for Victoria, Australia from multiple sources and file formats, brought it into a single consistent schema and analysed pricing information in different suburbs of Victoria. This information includes `house quarterly growth`, `median house price`, `house twelve-month growth` and more.<br>

Here are some instructions for viewing and reusing this code:

1. This activity has been performed with the Python programming language in Jupyter Notebook.
2. Description of each aspect of the code is given in the markdown sections of the notebook.
3. The data wrangling activity involved compiling the real estate data from different sources. Two of these sources (PDF and XML) are attached to this repository. To access the other sources, please note the next points.
4. The GeoJson Data and the Victoria Metropolitan Data can be found at this location: [Metropolitan-Location Data](https://drive.google.com/drive/folders/1LW_jwFj5yh132oYopo3shmAoVGfMwLgf?usp=sharing). In case of any issues in accessing the data, I can be contacted at my email ID: siddharthgupte@hotmail.com.
5. The real estate housing prices for Victoria were web-scrapped from: [Your Investment Property](https://www.yourinvestmentpropertymag.com.au/). Please note that this website may have undergone changes following the development of this project or it may be decommissioned in the future. Therefore, the web scrapping section of the code may require changes accordingly. However, I have saved the version of the web scrapped data from the time of project development. I loaded it into multiple text files for easier understanding. You may choose to reuse these data files directly instead of web scrapping from the website. They are:
   - `house_reports.txt`
   - `median_house_prices.txt`
   - `house_quarterly_growths.txt`
   - `house_average_annual_growths.txt`
   - `house_12_month_growths_list.txt`
7. The final schema containing the multi-sourced data is given in this repository.
8. Please use proper referencing and acknowledgement of the original author of this repository while reusing this code as decreed by the `GNU General Public Licence 3.0`.
