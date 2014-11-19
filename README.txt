README:

To use the program simply run the provided python file on any machine with Python 3.x. 
The program will ask for a path to a .json object to be processed. 
If the file is not in the same location as the python file you must enter a full (absolute) path to the file. 
If they are in the same directory a relative path (just the file name) will be adequate. After the program
runs it will prompt you to choose whether or not you wish to test the program against additional files.

If you wish to sort the output by path length rather than path weight a minor change to the source code is required.
Navigate to the display_results function definition and find the line "without_cycles.sort(key=sort_by_cost)" at line
217. Change "sort_by_cost" to "sort_by_length" and the output will now be organized by path length.

Michael Harris
					
