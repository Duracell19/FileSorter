# FileSorter
Sorter Utility which is sorting huge text files in format number. string. 
To run TestFileGenerator please use the following command:

cd ../TestFileGenerator/TestFileGenerator/bin/Debug/net8.0
dotnet TestFileGenerator.dll 

The result of generation ('unsorted_test_data.txt') will be located in ../TestFileGenerator/TestFileGenerator/bin/Debug/net8.0 folder.


Configurable options:

--file-size
Set size of the generated file (GB). Default size is 1 GB. Maximum value is 100 GB.

--max-string-length
Set maximum count of symbols for generated strings. Default value is 50 symbols. Maximum value is 100 symbols

--max-num-length
Set maximum count of symbols for generated number. Default value is 5 symbols. Maximum value is 7 symbols.

--repeatance
Set repeatance percentage. Default value is 60%. Maximum value is 100%.


To run SorterUtility please use the following command:

cd ../SorterUtility/SorterUtility/bin/Debug/net8.0
dotnet SorterUtility.dll 

Please rename the file which is required for testing to 'unsorted_test_data.txt' and put it to (../SorterUtility/SorterUtility/bin/Debug/net8.0) folder. By default the folder already contains generated file for 1GB.

The result of sorting ('sorted_test_data.txt') will be located in ../SorterUtility/SorterUtility/bin/Debug/net8.0 folder.


Configurable options:

--file-path
Set file path. Default value is 'unsorted_test_data.txt'.
