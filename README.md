# Oracle-Cloud-Infrastructure-for-Data-Science
### Configuring a Data Science Tenancy

First we need to create a Tanancy.  You can think of the tenancy as your account,
but it is also a secure and isolated partition within Oracle Cloud Infrastructure where you can create, 
organize, and administer your cloud resources. Following are the steps for it.

1. Creating a Data Scientists User Group.

2. Creating a Compartment for Your Work.

3. (Optional) Creating a VCN and Subnet.

4. Creating Policies.

5. Creating a Dynamic Group with Policies.

6. Creating a Notebook Session.

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

# Next step is Creating a Model Deployment
After you store a Data Science model in the model catalog, it can be deployed as an HTTP endpoint as model deployment.
Ensure that while creating the tanancy you have created the necessary policies, authentication, and authorization for model deployments.
Consider using a **custom container** when creating a model deployment.
You can create and run model deployments using the Console, the OCI Python SDK, the OCI CLI, or the Data Science API.

1. Creating a Container Instance [Click here](https://docs.oracle.com/en-us/iaas/data-science/using/models-about.htm)
2. Creating a Model Deployment  [Click here](https://docs.oracle.com/en-us/iaas/data-science/using/model_dep_create.htm)



