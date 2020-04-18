## Dataproc Project
Distributed Image Processing in Cloud Dataproc

# Setup
For this assignment I'm going to demo the Google qwicklab Dataproc project https://www.qwiklabs.com/focuses/5834?catalog_rank=%7B%22rank%22%3A7%2C%22num_filters%22%3A0%2C%22has_search%22%3Atrue%7D&parent=catalog&search_id=4914974

# Goals
1. Learn to use Apache Spark on Cloud Dataproc to distribute an image processing task onto a cluster of machines.
2. Create a managed Cloud Dataproc cluster with Apache Spark pre-installed.
3. Build and run jobs that use external packages that aren't already installed on your cluster.

# Background & Extra Info
If different subsets require different amounts of processing (or if you don't already know Apache Spark), Apache Beam on Cloud Dataflow is a compelling alternative because it provides autoscaling data pipelines.

In this lab, the job that you will run outlines the faces in the image using a set of image processing rules specified in OpenCV. The Vision API is a better way to do this, since these sort of hand-coded rules don't work all that well, but this lab is an example of doing a compute-intensive job in a distributed way.

# Demo
To see a representation of the demo and the output click the link below:

https://www.youtube.com/watch?v=QkwDK0gVTSc
