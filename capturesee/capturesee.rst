.. _capturesee:

CaptureSee
#########################

Summary
===================

CaptureSee enables the user to browse highly multiplexed CaptureSee experiments Initially, the user uploads a list of genomic locations and associated data, which can then filtered, sorted and viewed. Operations such as finding the nearest TSS, intersections with other annotations/views can also be carried out. In addition charts can be created based on any the the parameters (or combinations of) and  used to filter the data. Extra genomic tracks can be added and images generated for each location, so that trends in the data can be more easily recognised. Locations can be annotated (tagged) by the user and downloaded or exported to the data visualisation tool `Zegami <http://www.zegami.com>`_ for further analysis.

Creating a Project
===================



To create a project click on 'My Projects' (1) on the top navigation bar and then the  Multi Locus View panel (2). This will take you to a page where you have to fill in the name and description of the project (3). You also have to select the gemome required. If the genome you want is not available select 'other'. In this case gene information and other annotations will not be available. When you press 'Create' you wll be taken to a page where you can upload your file (see below)


Uploading Data
----------------
Press Choose in the displayed dailog and  select your file containing genomic locations. The file format is quite flexible and can be either tab(.tsv) or comma(.csv) delmited and also can also be gzipped (.gz) The only requirement is that the first three columns (in order)  specify the genomic location i.e. chromosome, start and finish. Normal bed files fulfill these criteria as well as excel data that has been saved as a .csv or .tsv file. The file will be parsed and the column (feild) types will
be ascertained.
