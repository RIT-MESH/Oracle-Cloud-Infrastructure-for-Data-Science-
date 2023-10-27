# Oracle-Cloud-Infrastructure-for-Data-Science
Here I tried to compile all the steps required for running the data science model in the Oracle Cloud Infrastructure.\
This may be useful for beginners.

### Configuring a Data Science Tenancy

First we need to create a Tanancy.  You can think of the tenancy as your account,
but it is also a secure and isolated partition within Oracle Cloud Infrastructure where you can create, 
organize, and administer your cloud resources. Following are the steps for it.

1. Creating a Data Scientists User Group. [Click here](https://docs.oracle.com/en-us/iaas/data-science/using/model-ads-save.htm#model-ads-save)

2. Creating a Compartment for Your Work. [Click here](https://docs.oracle.com/en-us/iaas/Content/Identity/compartments/To_create_a_compartment.htm)  [**Video Tutorial** Click here](https://www.youtube.com/watch?v=lqwchN7uH7g) 

3. (Optional) Creating a VCN and Subnet. [Click here](https://docs.oracle.com/en-us/iaas/Content/Network/Tasks/create_subnet.htm)

4. Creating Policies. [Click here](https://docs.oracle.com/en-us/iaas/Content/Identity/policymgmt/managingpolicies_topic-To_create_a_policy.htm)

5. Creating a Dynamic Group with Policies. [Click here](https://docs.oracle.com/en-us/iaas/Content/Identity/dynamicgroups/To_create_a_dynamic_group.htm)

6. Creating a Notebook Session. [Click here](https://docs.oracle.com/en-us/iaas/data-science/using/create-notebook-sessions.htm)

7. Creating a Custom Conda Environment [Click here](https://docs.oracle.com/en-us/iaas/data-science/using/conda_create_conda_env.htm) [**Video Tutorial** Click here](https://www.youtube.com/watch?v=5gGXE0Pe0ZY&list=PLKCk3OyNwIzv6CWMhvqSB_8MLJIZdO80L&index=6) 

8. Using Notebook Sessions to Build and Train Models  [Click here](https://docs.oracle.com/en-us/iaas/data-science/using/use-notebook-sessions.htm)

Documentation [Click here](https://docs.oracle.com/en-us/iaas/data-science/data-science-tutorial/get-started.htm)

Video Tutorial [Click here](https://www.youtube.com/watch?v=8LRQzPUwWzI&list=PLKCk3OyNwIzv6CWMhvqSB_8MLJIZdO80L&index=2)


### Next step is creating a Model Catalog
The model catalog is a centralized and managed repository of model artifacts. 
Models stored in the model catalog can be shared across members of a team and they can be loaded back into a notebook session.
Create a model and save it to the model catalog by using the ADS SDK, OCI Python SDK, or the Console.
Oracal recommend that you create and save models to the model catalog programmatically instead, either using ADS or the OCI Python SDK.
After you store a Data Science model in the model catalog, it can be deployed as an HTTP endpoint as model deployment.

1. Creating and Saving a Model with the ADS SDK [Click here](https://docs.oracle.com/en-us/iaas/data-science/using/model-ads-save.htm#model-ads-save) 

   
2. Creating and Saving a Model with the OCI Python SDK[Click here](https://docs.oracle.com/en-us/iaas/data-science/using/save-python-sdk.htm#save_python_sdk) 

   
3. Creating and Saving a Model with the Console[Click here](https://docs.oracle.com/en-us/iaas/data-science/using/model-console-save.htm#create-models) 


4. Exporting a Large Model Artifact[Click here](https://docs.oracle.com/en-us/iaas/data-science/using/large-model-artifact-export.htm#large-model-artifact-export) 

 
5. Importing a Large Model Artifact[Click here](https://docs.oracle.com/en-us/iaas/data-science/using/large-model-artifact-import.htm#large-model-artifact-export)

Video Tutorial [Click here](https://www.youtube.com/watch?v=WqjGz7Xckrs&list=PLKCk3OyNwIzv6CWMhvqSB_8MLJIZdO80L&index=12)

### Next step is Creating a Model Deployment
After you store a Data Science model in the model catalog, it can be deployed as an HTTP endpoint as model deployment.
Ensure that while creating the tanancy you have created the necessary policies, authentication, and authorization for model deployments.
Consider using a **custom container** when creating a model deployment.
You can create and run model deployments using the Console, the OCI Python SDK, the OCI CLI, or the Data Science API.

1. Creating a Container Instance [Click here](https://docs.oracle.com/en-us/iaas/data-science/using/models-about.htm)
2. Creating a Model Deployment  [Click here](https://docs.oracle.com/en-us/iaas/data-science/using/model_dep_create.htm)

Video Tutorial [Click here](https://www.youtube.com/watch?v=fBrD226vFl4&list=PLKCk3OyNwIzv6CWMhvqSB_8MLJIZdO80L&index=7)


### Invoking a Model Deployment
Invoking a model deployment means that you can pass feature vectors or data samples to the predict endpoint, and then the model returns predictions for those data samples.\
1.Invoking a Model Deployment [Click here](https://docs.oracle.com/en-us/iaas/data-science/using/model-dep-invoke.htm)


### Official OCI data science AI samples [Click here](https://github.com/oracle-samples/oci-data-science-ai-samples/tree/main)



