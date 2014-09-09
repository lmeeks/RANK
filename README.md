RANK
====

RANK tool for water resources network analysis

Please cite the refereed journal article:  Meeks, L. and Rosenberg, D. E. (2014) "Identifying and ranking stability, topological significance, and redundancies in water resource networks to guide detailed simulation modeling." Journal of Water Resources Planning and Management, In Review.

RANK is a network analysis tool to identify and rank stability, topological signifiance, and redundancy for networks. It builds on theories of parallel coordinates with statistical analysis to quantify and compare network nodes. The refereed hournal article details how the ranking results can be used to inform water management decisions such as future dam locations, the most critical locations for monitoring flows, promising sources for water transfers, and environmental areas in need of protection. RANK scales for small and medium networks, and the ranking of nodes can identify promising nodes to subsequently focus computationally-intensive simulation and sensitivity analysis efforts.  

RANK is available for download, as well as updated versions, at https://github.com/lmeeks/RANK. Note that the files for RANK are as is and there is no warranty. 

The tool's file name is Rank.xlsm which is a macro-enabled file. To use, select it from the file list and download it by clicking on "View Raw" in the github window. Make sure that editing and macros are enabled. RANK requires a square matrix with 1-link connections identified as an input for analysis. An example 10-node network Excel file is also available named ExampleNetwork.xlsx for users to try RANK before creating their own input matrix. 

The first worksheet in the RANK.xlsm workbook is the QuickStart Guide for instructions and introduction to the nomenclature used throughout the documentation.

The worksheet Example Network can be used to try the tool. It is a 10-node network with three sources, two sinks, and five intermediate nodes. The input matrix can be copied and pasted from the Excel sheet into RANK. When using Rank for the Example Network, good values to use the first time for the Threshold and Reducndancy Value are 3.0 and 0.75, respectively.
