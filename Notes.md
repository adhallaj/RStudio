# Moving around:
Console is essentially the terminal.

Navigation commands:

	ls() #list variables in workspace
	rm(x) #remove x from workspace
	getwd() #shows current working directory, R needs to be told what the working directory is.
	setwd() #sets working directory

# Definitions:

Vector: Sequence of data points that are the same type, combined with the c() if not already in a pre-existing data frame.

		vectora <- c(a,b,c)
		vectorb <- c(d,e,f)
		vectorc <- c(g,h,i)
		
Data Frame: List of vectors of equal length. Combine vectors into a data frame with the following command:

		vectorsabc <- data.frame(vectora, vectorb, vectorc)

