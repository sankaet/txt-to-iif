Quickbooks 2010 for Mac can't import any non-proprietary file format like CSV or tab-delimited files. This is a stupid simple Ruby script to convert a tab-delimited text file into an IIF file that can be imported into Quickbooks. It was written specifically to import deposits to an account register.

You can easily create tab delimited text files by copying data from a spreadsheet application and pasting it into a text editor. You can also save as tab-delimited text files from most spreadsheet applications.

Currently, the script assumes UNIX style line breaks.

Usage: ruby txt\_to\_iif.rb input\_file.txt > output\_file.iif

Warning: The IIF file format is unforgiving. Quicken and Quickbooks will import it without any regard for data integrity. If there are errors in the file, you can corrupt your Quickbooks or Quicken file. You should 1) back up your data file before importing and 2) test the import first on a very small sample of data (2-3 transactions) before running a larger import.
