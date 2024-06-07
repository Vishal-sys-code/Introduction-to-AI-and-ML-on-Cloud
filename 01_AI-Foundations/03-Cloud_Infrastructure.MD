# **Cloud Infrastructure**

Google has been working with data and AI since it's early days as a company in 1998. In 2008, Google Cloud launched to provide the secure and flexible cloud computing and storage services.

Google Cloud Infrastructure has 3 layers:
* **Networking and Security :** It lays the foundation to support all of Google's infrastructure and applications.
* **Compute and Storage :** GC separates or decouples as it's technically called, compute and storage so they can scale independently based on need.
* **Data and AI Products :** It enable you to perform task to ingest, store, process, and deliver business insights, data pipelines and ML models.

Google offers a range of the computing services they are:
* **Compute Engine :**  It is an infrastructure as a service, or IaaS, offering which provides compute, storage, and network resources virtually that are similar to a physical machine. We use the virtual compute and storage resources in the same as we would manage them locally. Compute Engine provides maximum flexibility for those who prefer to manage server instances themselves.
* **Google Kubernetes Engine :** GKE runs containerized applications in a cloud environment, as opposed to on an individual virtual machine like Compute Engine. A container represents code packaged up with all its dependencies.
* **App Engine :** It is a fully managed PaaS, or platform as a service, offering. PaaS offerings bind code to libraries that provide access to the infrastructure application needs.
* **Cloud Functions :** 
    * Code execution in response to events.
    * Serverless offering.
    * Functions as a service.
* **Cloud Run :**
    * It is a fully managed platform.
    * Lets us focus on writing code.
    * Automatically scales up and down.
    * Charges only for the resources you use.

***Where does the processing power comes from?***
The processing power comes from the hardware: from computer chips. The traditional computer chips like: Central Processing Units or CPU and even the most recent one that is Graphics Processing Units or GPUs may no longer scale to adequately reach the rapid demand for ML. So, Google overcome this challenge in 2016 by introducing the Tensor Processing Unit or TPUs. TPU is custom-developed application-specific integrated circuits(ASICs) used to accelarate machine learning workloads
