# Assets

## Description
Assets folder holds your input data for rounds and any external static dependencies for the other services.


## Downloads & Directory Structure
For JenTab to work properly, it requires static input and dataset files sourced externally. Files are linked in the Dependencies section. The structure goes as follows:
* `./Autocorrect` (optional): A brief description for autocorrect file.
* `./Baseline_Approach`: A brief description.
* `./data`: A brief description.
  * `./date/cache`: 

	'''
	+---Autocorrect
	|       GoogleNews-vectors-negative300.bin
	|       
	+---Baseline_Approach
	|       stopwords.txt
	|       
	+---data
	|   +---cache
	|   |   \---Generic_Lookup
	|   |           lookup.db3
	|   |           
	|   \---input
	|       \---2020
	|           +---Round 1
	|           |   +---tables
	|           |   \---targets
	|           +---Round 2
	|           |   +---tables
	|           |   \---targets
	|           +---Round 3
	|           |   +---tables
	|           |   \---targets
	|           \---Round 4
	|               +---tables
	|               \---targets
	\---Wikidata_Endpoint
			excluded_classes.csv
			excluded_colheaders.csv

	'''
	
## Dependencies
* [GoogleNews-vectors-negative300.bin](https://s3.amazonaws.com/dl4j-distribution/GoogleNews-vectors-negative300.bin.gz)
* [stopwords.txt](https://gist.github.com/sebleier/554280)
* [2020 Dataset per Round](https://www.cs.ox.ac.uk/isg/challenges/sem-tab/2020/index.html)
* [Generic_Lookup per Round](https://github.com/fusion-jena/JenTab_precomputed_lookup) "lookup.db3" in the Directory Structure
* Wikidata_Endpoint
	* [excluded_classes.csv](https://github.com/fusion-jena/JenTab/blob/main/assets/Wikidata_Endpoint/excluded_classes.csv)
	* [excluded_colheaders.csv](https://github.com/fusion-jena/JenTab/blob/main/assets/Wikidata_Endpoint/excluded_colheaders.csv)


