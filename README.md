This web-based application has been developed with inspiration drawn from the great work of my colleague https://www.linkedin.com/in/benjamin-larson-9692544/ at Vimeo.

The primary function of this application is to furnish a visual representation of Vimeo video view analytics over the last five weeks. It is designed to retrieve historical view data, identify the top ten performing videos by their aggregate view count, and subsequently render this information as an interactive heatmap. This visualisation facilitates a straightforward and immediate assessment of video performance trends and popular content across specified weekly intervals.

To run it, you must possess a valid Vimeo API token with the requisite permissions to access their account's analytics. Activation of the "Generate Heatmap" button will initiate the data retrieval and processing sequence, culminating in the display of the heatmap.

The visualisation component of this application is powered by ECharts, an open-source JavaScript library. The overall logic of the app can be illustrated thus:


![image](https://github.com/user-attachments/assets/c52bba57-6235-4499-9237-fe82f41b6997)
