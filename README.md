# Introduction 
Deploy the following
1. Azure Machine Learning Service (1.workspace)
2. Compute Instance (2.compute_instance)
3. AML Compute Training Cluster (3.amlcompute) 

# Getting Started
1. Create a service principal.
2. Create a resource group for a virtual network.
3. Create a virtual network in the above resource group.
4. Assign the above service principle Contributor rights to above virtual network resource group.
5. Create a resource group to deploy Azure Machine Learning workspace.
6. Assign the above service principle Contributor rights to above resource group where the machine learning workspace will be deployed to.
7. Import the pipeline from the pipelines folder.
8. Add the above service principal as a service endpoint
9. Update the configuration in the pipeline to correct paths to the templates and also the parameters.
10. Create a release and run the release.
