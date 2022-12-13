Gene Search
____________

For spatial ATAC data, AtlasXplore can be used to check the gene score of certain gene/genes. The gene score is a prediction of how highly expressed a gene will be based on the accessibility of regulatory elements in the vicinity of the gene.

Access AtlasXplore at https://web.atlasxomics.com/

**Navigating the Menu**
####################################################

.. image:: /images/1.png

From left to right: 

*Gene Motif:*
Lists the species (mouse, rat, human, etc), Organ, Type, and Run ID. 

To switch between the gene and motif datasets click *GENE*.

To change the background color click the paint pallete icon. 

To change the heatmap color click the flame icon. 

To upload an ID CSV file, click the up arrow to populate the gene viewer. 

To search any gene ID, type or select in the search bar. Can select as many genes as needed (no limit). Click *Show*.

To view cluster, average of all gene scores, and the name of the gene and its gene activity score hover over any tivel. 
Can select or deselect clusters on the right. 

**Feature table** 
####################################################
Lists top 10 ranked genes in each of the clusters. 
The feature table displays the data values as rows, with each row representing a different gene. The columns of the table can include various types of information, such as the name of the feature, the genomic coordinates, and the data values.

The feature table can also be used to sort and filter the data, allowing users to focus on specific subsets of the data and to perform more detailed analyses.

.. image:: /images/3.png

**Clustering**
####################################################
Clustering can be used to group similar features within the genome, such as genes or regulatory elements. This can be useful for identifying groups of genes that are co-regulated or that have similar functions, or for identifying conserved sequence features across multiple species.

To perform clustering, users can use the "Cluster" menu located at the top of the Genome Browser. This menu allows users to specify the data to cluster, the clustering method to use, and any additional options, such as the distance metric and the number of clusters.

Once the clustering has been performed, the results will be displayed in the Genome Browser, with each cluster represented by a different color. Users can then view and analyze the clusters by navigating to different regions of the genome and by using the other tools and features of the Genome Browser.

**Heat Map**
####################################################
A heat map can be used to display the values of a data set, such as gene expression levels or conservation scores, across a genome or other data set. The x-axis of the heat map represents the genomic coordinates, and the y-axis represents the data values. The colors in the heat map indicate the magnitude of the values, with warmer colors representing higher values and cooler colors representing lower values.

Heat maps are useful for identifying patterns and trends within the data, such as regions of the genome that have high or low levels of gene expression or conservation. They can also be used to compare data sets, such as to compare the expression levels of different genes or to compare the conservation scores of different species.

To view the heat map for select genes, click any of the listed genes to automatically enter it in the search bar. If your gene of interest is not listed, you can enter it in the search bar. Click the gene in the search bar so that it turns orange and click *show*. Now you’ll be able to view the heat map for the selected gene and repeat the process to view multiple genes at once.

.. raw:: html

    <iframe width="560" height="315" src="https://www.youtube.com/embed/pF67XlJGWZE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

