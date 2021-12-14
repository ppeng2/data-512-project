# data-512-project
> Written with [StackEdit](https://stackedit.io/).

This project consists of two loosely related parts, a Common Analysis (A4) and an Extension Analysis (A5), pertaining to the COVID-19 pandemic in [Milwaukee County, Wisconsin](https://en.wikipedia.org/wiki/Milwaukee_County,_Wisconsin). This project was done for credit in DATA 512, Human Centered Data Science, as part of the MS in Data Science program at the University of Washington during the Autumn 2021 term.

## License
MIT License. See the `LICENSE` file.

## Contents of this Repository
 * The `data` folder contains the datasets used in this project. See **Data Provenance** below.
 * The `notebooks` folder contains the Jupyter notebooks used to perform the data cleaning and analysis for this project.
	 * `a4-common-analysis.ipynb` contains the work done for the Common Analysis (A4).
	 * `a5-extension-analysis.ipynb` contains the work done for the Extension Analysis (A5).
	 * `eda-for-a5.ipynb` contains preliminary exploratory analysis of the data used for A5, in addition to other datasets that were ultimately not used.
 * The `written_reports` folder contains written material for this project in PDF format.
	 * A4 Common Analysis writeup 
	 * A5 Extension Plan proposal
	 * A6 project presentation
	 * A7 final report

## Data Provenance
The data used in the Common Analysis (A4) comes from three sources:
* `RAW_us_confirmed_cases.csv` is part of the [COVID-19 Data Repository](https://www.kaggle.com/antgoldbloom/covid19-data-from-john-hopkins-university) maintained on Kaggle by Johns Hopkins University. This dataset updates daily, and was downloaded on October 31, 2021. It is licensed [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
* [Information on masking mandates by county](https://data.cdc.gov/Policy-Surveillance/U-S-State-and-Territorial-Public-Mask-Mandates-Fro/62d6-pm5i) comes from the US CDC and is under the [US Public Domain](http://www.usa.gov/publicdomain/label/1.0/).
* `mask_use_by_county.csv` comes from the [Mask-Wearing Survey Data](https://github.com/nytimes/covid-19-data/tree/master/mask-use) repository and is provided by The New York Times and Dynata.

The Extension Analysis (A5) uses the COVID-19 Data Repository dataset from A4, and additionally uses data from the following sources:
* `trafficaccident.csv` comes from the [City of Milwaukee Open Data Portal](https://data.milwaukee.gov/dataset/trafficaccident). It is licensed [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
* [Traffic counter data](https://transportal.cee.wisc.edu/products/hourly-traffic-data/bysiteid/milwaukee.html) (in the `/data/CT-400003/` folder) from WisDOT continuous counter #400003, located on Interstate 94 at 26th Street, west of downtown Milwaukee, is provided by the TOPS Lab at the University of Wisconsin-Madison. 