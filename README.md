# entropy-nlp-ocr

A major challenge in developing this pipeline was due to the nature of files being faulty I had to create separate templates per file.

However, one method that I was able to apply to all files was matching the test names from the file and extracting relevant rows.

Then applying transformation to separate parameters from values by applying the regular expression method.

Finally using a bit of manual + string split methods to format the data into correct shape with 3 columns namely: 'parameter', 'value' and 'unit'. 
