Genome Browser
_______________

AtlasXplore uses the BioDalliance Genome Browser to display peaks, raw fragments per cluster, and gene model for the corresponding gene being searched. User can also use the Genome Browser to compare spatial data with other data sets.

For example, if a user is searching for a specific gene, the Genome Browser can display the gene model for that gene, along with any associated peaks and raw fragments per cluster data. This allows the user to see the spatial relationship between the gene and the other data sets, and to compare this relationship to other genes or data sets.

In addition to viewing and comparing data sets, the Genome Browser includes tools for analyzing and manipulating the data. Users can zoom in and out, pan, and search for specific features within the genome. They can also use the browser to perform various types of analyses, such as motif searches and gene expression analysis, to better understand the data and gain insights into the underlying biology.

**Features**

Genome Browser includes a number of features and tools for exploring, analyzing, and understanding genomic data, including:

*Support for multiple genome assemblies and annotation tracks:* allows users to view and compare different genome assemblies and annotation tracks, such as genes, regulatory elements, and functional features.

*Interactive visualization:* The Genome Browser includes tools for zooming, panning, and searching within the genome, allowing users to easily explore and navigate the data.

*Overlaying of data sets:* allows users to view and compare additional data sets, such as peaks and raw fragments per cluster, that can be overlaid on top of the genome.

*Analysis tools:* Genome Browser includes tools for performing various types of analyses, such as motif searches and gene expression analysis, to gain insights into the underlying biology of the data.

.. raw:: html

    <iframe width="560" height="315" src="https://www.youtube.com/embed/wmv6G4RbtNw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


**Navigation**

Navigate to Peak Viewer by clicking the second icon to the left of the *Feature Table*. 
Once your genes are selected, you should see a genome view like this

.. image:: /images/4.png

 To view the base-pair-level genome sequence, zoom in greater than 500bp. 
 Toggle between two zoom levels by tapping the space bar.

 Double-click on any feature to center it, then zoom in to find other features which might be aligned with it. 
 For larger features, double-click close to the edges of the feature to center that edge.

 To jump to a gene location, gene name, or specific coordinates, type it in the location box in the toolbar. If a named feature can be found in any   searchable track you currently have active, it will be highlighted in the browser, like this:

.. image:: /images/5.png

 To select a track click its label once, this is called *Leaping*. Activate *Leaping* by clicking the left and right buttons in the toolbar. *Leaping* will  take you to the next feature in that direction. 

 To customize tracks select one then open the *Track Editor*, the road icon. 
 Change the order of tracks by dragging the name-tabs and dropping it elsewhere in the browser display. Can reset the browser from the Settings panel.

.. image:: /images/6.png

**Adding Data**

To add data to the Genome Browser, users can use the "Add track" menu located at the top of the browser. This menu allows users to choose from a variety of
data sources, such as local files, remote files, and indexed databases. Users can also specify the format of the data and any additional options, such as
the track name and the visibility of the track.

Once the data has been added, it will appear in the track list on the left side of the Genome Browser. Users can then view and analyze the data by clicking
on the track name and navigating to the region of interest within the genome.

To add a new track or select/ deselect clusters, click the plus icon. 
 
.. image:: /images/8.png

 To add arbitrary Distributed Annotation System (DAS) data by running your own DAS server, add custom track or lab-specific data 

.. image:: /images/9.png

 To add indexed binary files, click *Binary* and upload bigBed, bigWig, BAM, or .2bit file.

.. image:: /images/10.png

 To view all keyboard shortcuts, click the question mark icon

.. image:: /images/11.png

**Export Data** 

To export data from the Genome Browser, users can use the "Export" menu located at the top of the browser. This menu allows users to export the data in
various formats, such as BED, GFF, and FASTA. Users can also specify the region of the genome to export, and any additional options, such as the export
filename and the data format.

 To export the data as an image, SVG, or Dalliance page by clicking the printer icon. 

.. image:: /images/7.png

**Histograms**

The histogram for TSS enrichment and fragments is a tool that allows users to visualize and analyze the distribution of transcription start sites (TSSs)
and fragments within a genome or other data set.

TSSs are the starting points of transcription, where the process of converting DNA into RNA begins. TSS enrichment is a measure of the number of TSSs
present in a given region of the genome, and can be used to identify regions of active transcription or gene regulation.

Fragments refer to small pieces of DNA or RNA that are generated during various biological processes, such as DNA replication or RNA degradation. The
number and distribution of fragments within a genome can provide insights into the underlying biology and can be used to identify specific features or
patterns.

The histogram for TSS enrichment and fragments allows users to visualize the distribution of these values within a genome or other data set. The histogram
can be used to identify regions of the genome that have higher or lower levels of TSS enrichment or fragment density, and to compare these values to other
data sets or to other regions of the genome.

To view the histogram for TSS Enrichment and Fragments, click the third icon, the bar graph, to the left of the *Feature Table*
The x-axis is the *gene score*
The y-axis is the number of *tixels*

.. image:: /images/12.png
