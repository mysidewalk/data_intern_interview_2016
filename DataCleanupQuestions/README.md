Data Cleanup
============

In this data file (sample_data.txt), there are three records.

In your favorite scripting language (we use Python at mySidewalk), write a few functions/methods that will:

• Convert all strings to Title Case (e.g. ``SUGAR LN`` becomes ``Sugar Ln``).
• Remove stray spaces inside a string.
For e.g.
```python
PALESTINE                                         TX
```
should become 
```
PALESTINE TX
```
• The last field in each record is the Date of Birth (represented as yyyymmdd). Calculate the individual's age today.

Now, use all those functions/methods to process the entire file, and print the output line-by-line into the console.

Use any scripting language you like, but please make sure you've got some documentation explaining
your thought process.
