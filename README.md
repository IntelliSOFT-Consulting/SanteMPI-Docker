This a quick start for users who wish to test-drive the SanteMPI project on Docker. 

**NOTE:** This is intended as a beginner level introduction to get users up and running with the SanteMPI project. Developers of SanteMPI plugins or triggers will need additional tooling. 
Additionally, this should not be used for production environments.

## Pre-Requisites

This tutorial uses Docker as a basis for illustrating SanteMPI functions. In order to complete this tutorial, users should:

* Have Docker installed on the host system (on Windows or Linux)
* Have Docker Compose installed

## Start the Docker Application


```
cd santempi-docker
docker-compose up -d
```

This will start the SanteDB iCDR (running SanteMPI), the web access gateway and database. Initial startup of the SanteMPI container can take upwards of 5 minutes. You will see a log entry which indicates that startup was successful after this time.

## Complete the Tutorial

The complete Quick-Start tutorial can be found on the [SanteDB Wiki - Quick Start](https://help.santesuite.org/installation/quick-start-guide)