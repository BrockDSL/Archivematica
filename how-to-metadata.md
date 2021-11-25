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

`filename`


