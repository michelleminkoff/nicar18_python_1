Files and code for a Python 1 hands-on session at NICAR18 in Chicago

# Outline for hands-on session

1. Open a Jupyter notebook file (link to download)
	* Remember - hit Shift-Enter to run a cell!

2. Overview of why this is a good language to learn on, how it may be different from others
	* Reliance on indentation
	* Loose vs. strict typing
	* Lots of built in functions and modules that can be imported
	* (Show XKCD comic here: https://xkcd.com/353/)
	* Do basic math
	* Print out some text
	* Integrate result in a sentence
	* Print it out

3. Data types
	* Variables
	* Numbers
	* Strings
		* Important functions:
			* Slice (use numeric indices, -1 counts from end)
			* Lower/upper
			* Strip
			* Startswith
			* Find - look for a string within a string
	* Booleans
	* Lists
		* Join function
	* Dictionaries

4. Iteration
	* Demonstrate sample with a list like ["dog", "cat"]
	* Take our data file and load each row individually, to show what looping is

5. Comments
	* Why do we use comments?
	* How do we add them to a file?

6. Importing modules
	* Load a sample module
	* Where do we load it?
	* What name do we use when referring to it?
	* What's the difference between targeting a library and a module? (ex: from x import y)
	* import datetime
			oTime = datetime.datetime.now()
			print oTime.isoformat()

7. Pip (to gain access to more modules)
	* explain how some modules built in/some can be pulled down
	* walk through online directory of what modules exist
		* PyPi index
		* https://wiki.python.org/moin/UsefulModules#Database
	* pull one down - like pip install pandas

8. Start use of Pandas to load and manipulate file
	* find current directory with os.getcwd()
	* We will use this file: https://catalog.data.gov/dataset/sex-offenders-938b3
	* import pandas as pd
	* input = pd.read_csv(PATH_TO_SEX_OFFENDERS_DATABASE);
	* #row
	* input.iloc[1]
	* #column
	* input['TOTAL CASES']
	* #row and column
	* input.iloc[3]['TOTAL CASES']