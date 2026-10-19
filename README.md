This Project is dedicated to deploying and managing a cicd pipeline on a modern yet simple fast api based webapp with a simple html code popping when yu searvh my webapp,
and a simple api endpoint returning a json format. The hard work obviously wasnt in me making the webapp, but managing to deploy it via a kubernetes Cluster, spesifically the K0s zero friction 
flavour of Kubernetes.

1. Why to do this project? All modern software and in our case web applications , web servers etc, need a strong and most important scalling infastructure, that runs on any machine the same , and the developing team doesnt need to make prayers every time the push a new feature or change an old one . that why Kubernetes is king in modern architectural enviroments . Basically what i did is setup yamls for the proper ifastructure of the cluster, (k8s dile) , the yamls for the cicd pipeline and the proper configurations inside the cluster for the cd part and the python code that uses the fast api to make the webapplication and the simple api to work and be async.

2. The Architecture Of the Project:

        
