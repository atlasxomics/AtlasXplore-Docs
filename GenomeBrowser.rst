Genome Browser
_______________

AtlasXplore uses the BioDalliance Genome Browser to display peaks, raw fragments per cluster, and gene model for the corresponding gene being searched. User can also use the Genome Browser to compare spatial data with other data sets.

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
 To add a new track or select/ deselect clusters, click the plus icon. 

.. image:: /images/8.png

 To add arbitrary Distributed Annotation System (DAS) data by running your own DAS server, add custom track or lab-specific data 

.. image:: /images/9.png

 To add indexed binary files, click *Binary* and upload bigBed, bigWig, BAM, or .2bit file.

.. image:: /images/10.png

 To view all keyboard shortcuts, click the question mark icon

.. image:: /images/11.png

**Export Data** 
 To export the data as an image, SVG, or Dalliance page by clicking the printer icon. 

.. image:: /images/7.png

**Histograms**

To view the histogram for TSS Enrichment and Fragments, click the third icon, the bar graph, to the left of the *Feature Table*
The x-axis is the *gene score*
The y-axis is the number of *tixels*

.. image:: /images/12.png
