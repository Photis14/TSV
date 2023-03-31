# Frequency Table Processor
This program processes a frequency table file containing frequencies of words and expressions used by adolescents and young adults engaged in a certain unhealthy activity. The program adds another column to the table containing the mean frequency value of each row. The resulting table is saved into a new file in the same format as the original file.

# Input File Format
The input file is a tab-separated value (TSV) file with no header row. The first column lists the words, and the remaining columns list frequencies as floating-point numbers. Some columns may have missing values designated as empty strings.

# Output File Format
The output file is a tab-separated value (TSV) file with no header row. The first column lists the words, and the remaining columns list frequencies as floating-point numbers, including the new column added by the program. Missing values are designated as empty strings.

# How to Use
- Download or clone the repository to your local machine.
- Copy the frequency table file you want to process to the root directory of the repository.
- Open a terminal in the root directory of the repository.
- Run the program using the command python freq_processor.py input_file.tsv output_file.tsv, where input_file.tsv is the    name -of the input file and output_file.tsv is the name of the output file you want to create.
- The program will add a new column to the table and save the resulting table to the output file.
- Dependencies
- This program requires the csv module to read and write TSV files. The module is included in the Python standard library and does not require installation.
