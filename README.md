# Crowdfunding_ETL

### Project Team: Katie Starns and Amanda Hinkle

## Project Background

This is a project that focuses on extracting and transforming data using Python, Pandas, and either Python dictionary methods to build an ETL pipeline. The raw data provides information on crowdfunding projects, and is divided into two rough sections: campaign information and contact information. With this in mind, our job is to complete the pipeline to extract and visualize specific portions of that data. 

### Project Instructions

The instructions for this mini project are divided into the following subsections:

* Create the Category and Subcategory DataFrames
* Create the Campaign DataFrame
* Create the Contacts DataFrame
* Create the Crowdfunding Database

## Project Files

### .gitignore

This file indicates portions of files that are intentionally untracked. These files will be ignored by Git.

### ETL_Mini_Project_KStarnes_AHinkle

This is a Jupyter Notebook file. This file, through collaborative coding efforts, imported various files of xlsx data to be manipulated, adjusted, and exported into various data frames. This file serves as the blueprint for how the data frames were created, as well as shows the changes made to each of the files for easier reading and understanding. 

### campaign.csv

This is a csv file type with data specifically regarding the crowdfunding campaign data. This data is an overview of the company, their crowdfunding goals, the timeline of the crowdfunding events, the category and subcategory it falls under, and whether the crowdfunding was succesful.

### category.csv

This is a csv file type with the category id, found in the campaign.csv file, and the name of the corresponding category.

### subcategory.csv

This is a csv file type with the subcategory id, found in the campaign.csv file, and the name of the corresponding subcategory.

### contacts.csv

This is a csv file type with the contact's ID, name, and email address. The contact_id is linked to the contact_id found in the campaign.csv file.

### contacts.xlsx

This is the raw data that was imported and manipulated to create the data frames and obtain sorted information.

### crowdfunding.xlsx

This is the raw data that was imported and manipulated to create the data frames and obtain sorted information.
