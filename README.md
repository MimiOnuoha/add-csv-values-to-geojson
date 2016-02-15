# Add Values from a CSV to Geojson
---

This code is really basic: it takes in a CSV file with one column of values (including a header) and appends that column to the properties array of an existing geojson file. 

Make sure that your geojson features array and csv column have the same number of values (see included "samplecsv.csv" and "samplestates.json" for examples).

To run, clone this directory:

	git clone https://github.com/MimiOnuoha/add-csv-values-to-geojson

Make sure that your geojson and CSV files are in the same directory. Run using the following, substituting your filenames in where appropriate:
	
	python add_csv_to_geojson.py csvfile.csv geojsonfile.json
	
NOTE: Dependencies include the json, csv, copy, and sys modules. Make sure that you have installed each of them before using this. 


Sample installation (do for all that are not yet installed):

	pip install json
	

(If the above does not work, you may need to sudo it.)

*This code was created for the ITP Spring 2016 class "[Everything is Physical: The Art of Digital Mapping](https://github.com/MimiOnuoha/art-of-digital-mapping-ITP2016)."*

