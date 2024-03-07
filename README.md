# Equitel patterns test
~ This binary aims to test Equitel MSISDN Ranges (See bellow link).
	https://www.dignited.com/57218/safaricom-introduces-new-prefix-numbers-0110-and-0111/

# Requirements:
- Download or install java 21 on your workstation 
- Download this binary EquitelPattern.jar 

# Running the binary:
- To run the binary navigate to its directory and run bellow command

	java -jar EquitelPattern.jar 0778224569 0768224569 0714224569

The numbers can be more or less. 

# Sample Results
$ java -jar EquitelPattern.jar 0778224569

	- 0778224569 does not match Equitel MSISDN pattern

$ java -jar EquitelPattern.jar 0768224569

	- 0768224569 matches Equitel MSISDN pattern
