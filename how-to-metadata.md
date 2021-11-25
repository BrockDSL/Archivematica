# Archivematica metadata guide

## What is metadata?

**Metadata** is data about data. In this project, our metadata describes the air photos and helps us identify them. 

Metadata can either describe an object (object-level metadata) or a collection (collection-level metadata). 

In our case, collection-level metadata for the 1921 series of air photos might say something like, "A collection of air photos covering the Niagara Region in 1921." Item-level metadata for the 1921 series would focus on one air photo, and might say something like, "An overhead view of the Welland Canal, 1921." These are just examples, however.

## Formatting the metadata.csv file

You must import data via a CSV file. You can make your CSV file in Excel or in a text editor.

(example screenshot)

The above screenshot shows how to organize the metadata.csv file.

Blue arrow: transfer-level metadata for top-level "objects" directory in transfer

Orange arrow: item metadata for a file in "objects" folder

Red arrow: subdirectory-level metadata for a folder within objects

Green arrow: file-level metadata for items in a subfolder of the "objects" directory

## Archivematica Bag metadata

Archivematica requires the use of a few metadata fields. It recognizes Dublin Core fields only. 

In the above screenshot, the Dublin Core fields are bolded for emphasis only.

Here are some fields we will be using and their definitions:

`filename` - filename for the folder or file you are assigning metadata to in the row

`dc.title` - title of the folder or file. This might be something like "1921 Air Photos, Line 6."

`dc.creator` - name of the person or organization who collected or created the images

`dc.date` - date the original air photos were taken. In our case, type `1921`, or whichever year you are working on

`dc.subject` - subject of the object. In our case, something like `air photo`, `canal`, and anything relevant. Add a new column with the column header `dc.subject` for each subject.

`dc.description` - a short description of the object. Something like "air photo of Niagara Region in 1921." Please provide the line number or identifier of the air photo, which is available in the filename or on the image itself.


