# OpenCV-Video-to-Frame
This repository contains the notebook I created for parsing raw video into frames, converting to JPG and storing in Azure Blob or Azure Data Lake Gen 2 for annotation and/or training in Azure Machine Learning Studio.  If you're looking to easily convert video, this simple notebook saves a tremendous amount of time!

To use this in Azure Machine Learning Studio, you can simply download the notebook and upload it to your environment.  The comments inside of the notebook should be straightforward, as the only variablility is whether you're using Azure Blob Storage or Azure Data Lake Gen 2 (blob + hierarchical namespace + ACLs).

I hope you find it useful!
