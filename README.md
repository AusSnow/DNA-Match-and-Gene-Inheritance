# DNA-Match-and-Gene-Inheritance
This repository contains a program for matching dna of an individual to a database and a program simulating the inheritance of blood types.
# DNA-Match Usage
This program includes two test databases and twenty strings of dna to work with. After compiling the program you can run it in the command line with "python dna.py <csv-file> <dna-sequence>". For example, try running "python dna.py databases/small.csv sequences/1.txt" and the program should return Bob. By providing a database with the largest strings of STRs or short tandem repeats found consecutively and text files of the dna sequence you wish to test you can find the dna match if it exists in the database.
# Gene-Inheritance Usage
This program simulates the inheritance of blood types. After compiling the program you can run it in the command line with "./inheritance". This will simulate three generations, randomly assigning bloodtype to the oldest generation, and randomly picking existing alleles for descendants. Feel free change the generations const to simulate more generations, add user input for simulating set alleles of certain blood types, or create trees to see all possibilities with starting alleles.
