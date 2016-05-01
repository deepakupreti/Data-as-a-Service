-----------------------------------------------------------Data as a Service-----------------------------------------------------------
- Dependencies:
	- Hadoop Cluster for HDFS (link: http://www.michael-noll.com/tutorials/running-hadoop-on-ubuntu-linux-multi-node-cluster/)
	- Spark Cluster for Spark SQL processing (link: http://spark.apache.org/docs/latest/spark-standalone.html)
	- Web2py for appserver
- Installation:
	- After Hadoop cluster installation, Deploy FileServer.py on namenode and run as:
		python FileServer.py 5555
	- After Spark cluster installation, Deploy SparkServer.py on Spark master and run as:
		python SparkServer.py 5555
	- Deploy web2py.app.sparkapp.w2p to Spark master with Web2py running by importing as existing applications
		Run web2py on port 8000

	
