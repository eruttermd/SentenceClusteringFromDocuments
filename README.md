# Sentence Clustering from Documents

## Description
* Text from different documents can be saved in separate rows in the Excel worksheet.
* The script will split the text into sentences, each in a separate row, and create the indicated number of clusters based on Cosine Similarity scores.

## Run Jupyter Notebook in Google Colab
* Open Google Colab https://colab.research.google.com/
* Click on the GitHub tab.
* Paste the link to the GitHub repository that contains the Jupyter Notebook you want to run in the search and press Enter.
* Select the correct repository from the dropdown select box.
* Click the link for the Jupyter Notebook that should appear below.
* Click the folder icon on the left side of the window to open the files pane.
* Click the Upload to Session Files icon to upload any needed data file.
* Make sure the file name matches in the first cell of the notebook.
* Start at the top of the notebook and run the code in each cell.
* Enter the desired number of clusters in the cell that has the ClusterCount variable.
  * (I mixed sentences from three different Wikipedia pages to create the sample documents. How well does clustering put the topics back together?)
* After a minute or two the report file should appear in the files pane.
* Download the report file to see the cluster assignments in Excel.
