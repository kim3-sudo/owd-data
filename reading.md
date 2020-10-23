# Reading the text exports

Each file represents one diary, cataloged and transcribed to the best of the researchers' ability. Each file contains the following information:

- The first line is a catalog number from the original collection project. It is about as useful as an accession number. It looks like the following:
```
GWD0000001 wo/95/1103/1
```
- The second line describes the diary's purpose itself: what was the squad or division? Keep in mind that this data is specific to the British Royal Army in the early 20th century, and terms used then might be different today. It looks like the following:
```
1 CAVALRY DIVISION: 7 Brigade Royal Horse Artillery and Ammunition Column
```
- The third line indicates how many pages were found in the diary. A page is defined as one "sheet" or "report".
- The fourth line should be blank.
- The fifth line beyond describe the contents of the diary. It might contain the following:
  + The type of the page: a `cover` or `diary`
  + The date of the diary page's writing
  + Any activity that took place that day
  + Any people that were involved
  + And places that were involved
  + Any times that were logged
  + Each of these lines ends in a 1, 2, or possibly 3 digit number. This reference number is for finding the actual data in the diary itself, which can be found by going to the website indicated on each diary page.
- Keep in mind that some pages contain information from multiple days.
- Remember that this data was not written for a wide historical audience - it was designed to serve historians with the assistance of computer scientists and statisticians. The data processing scripts (largely unchanged since their writing) were made in Perl, and can be found [here](https://github.com/kim3-sudo/OWD.git).
