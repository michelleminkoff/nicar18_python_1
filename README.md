Files and code for a Python 1 hands-on session at NICAR18 in Chicago

#Possible data sets
	- Simpler FBI hate crimes stats (by state): https://ucr.fbi.gov/hate-crime/2016/tables/table-12 (fbi_hate_crimes_by_state.xls)
	- More complex FBI hate crimes stats (state and agency): https://ucr.fbi.gov/hate-crime/2016/tables/table-13/table_13_hate_crime_incidents_per_bias_motivation_and_quarter_by_state_and_agency_2016.xls/view (hate_crimes_fbi_state_and_agency.xls)
	- Simpler workplace accidents (Industry by event or exposure): https://www.bls.gov/iif/oshcfoi1.htm#2016 (fatal_accident_simpler.xlsx)
	- More complex workplace accidents (Event or exposure by age): https://www.bls.gov/iif/oshcfoi1.htm#2016 (fatal_accident_by_event_exposure_and_age.xlsx)


# Tentative outline for hands-on session

1. Overview of why this is a good language to learn on, how it may be different from others
	* Reliance on indentation
	* Loose vs. strict typing
	* Lots of built in functions and modules that can be imported
	* (Show import gravity comic here)
2. Writing basic code in the console
	* Do basic math
	* Print out some text

3. Creating code in a script
	* Do basic math
	* Integrate result in a sentence
	* Print it out

4. Running a script
	* Path to a script
	* Show scripts can be run with "python" and script path
	* Discuss what is/isn't viewable from console

5. Data types
	* Numbers
	* Strings
		* Important functions:
			* Slice
			* Lower
			* Strip
			* Starts with
			* Find
	* Booleans
	* Lists
		* Join function
	* Sets
	* Dictionaries

6. Iteration
	* Demonstrate sample with a list like ["dog", "cat"]
	* Take our data file and load each row individually, to show what looping is
7. Comments
	* Why do we use comments?
	* How do we add them to a file?
8. Importing modules
	* Load a sample module
	* Where do we load it?
	* What name do we use when referring to it?
	* What's the difference between targeting a library and a module? (ex: from x import y)
9. Pip (to gain access to more modules)
	* explain how some modules built in/some can be pulled down
	* walk through online directory of what modules exist
	* pull one down