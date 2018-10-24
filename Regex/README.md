# REGEXto filter through credit card numbers list

This app allows you to sift through a list and print credit card numbers that satisfy two conditions:

1- must 16 digits
2- they might contain hyphens
the formula for the regex number sequence is : 
# r'^(\d{4}\-?){3}\d{4}$'
this formula does not define the actual rules of cc numbers but provides the basic structure of a 16 digit number that may or may not be hyphenated.

to execute, "cd" into Regex folder from terminal, then the following python script:

" python find_cc_regex.py -F ccnumbers.txt "


