
### What is this?

Metagoofil is a tool for extracting metadata of public documents (pdf,doc,xls,ppt,etc)

This new version will also extract emails addresses from PDF and Word documents content

### How it works?

The tool first perform a query in Google requesting different filetypes that can have useful metadata (pdf, doc, xls,ppt,etc), then will download those documents to the disk and extracts the metadata of the file using specific libraries for parsing different file types (Hachoir, Pdfminer, etc)


### How to use
```bash
  metagoofil.py -d apple.com -t doc,pdf -l 200 -n 50 -o applefiles -f results.html
  metagoofil.py -h yes -o applefiles -f results.html (local dir analysis)
```

### Dependencies:
------------
In this version all depencies are included


Thanks Christian Martorella. 
