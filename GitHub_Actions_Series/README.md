GitHub Actions for Azure

This series will discuss how to automate your workflows on any GitHub event, such as code commits, creation of pull requests, and more. Then, deploy to Azure (CI/CD for Kubernetes & serverless apps), learn how to automate governance & security, and accelerate development with visual studio code extension & CLI.

### [Deploying apps on Azure web apps using GitHub Actions](https://www.meetup.com/microsoft-reactor-bengaluru/events/279015119/)

* Introduction to GitHub Actions
* Getting started with GitHub Actions
* Deploying app on Azure web app using GitHub Actions

|     Source Code     |    Reference    | Video |
|     :---    | :---           | :---:       |
| [GitHub repo - App Service](https://github.com/vivsridh4/quickstart)   | [Deploy a custom container to App Service using GitHub Actions](https://docs.microsoft.com/en-us/azure/app-service/deploy-container-github-action?tabs=publish-profile)  |      [Recording](https://www.youtube.com/watch?v=dyTXblcbqtg&t=1495s&ab_channel=MicrosoftReactor)   |


### [CI/CD with GitHub Actions for Kubernetes & Serverless apps](https://www.meetup.com/microsoft-reactor-bengaluru/events/279015137/)

* Deploying serverless app 
* Deploying containers and kubernetes app

|     Source Code     |    Reference    | Video |
|     :---    | :---           | :---:       |
| [GitHub repo - Azure Functions](https://github.com/vivsridh4/funcapp)<br/>[GitHub repo - Azure Kubernetes Service](https://github.com/vivsridh4/azure-voting-app-redis) | [Continuous delivery by using GitHub Action](https://docs.microsoft.com/en-us/azure/azure-functions/functions-how-to-github-actions?tabs=python)<br/>[Prepare an application for Azure Kubernetes Service](https://docs.microsoft.com/en-us/azure/aks/tutorial-kubernetes-prepare-app)<br/>[GitHub Actions for deploying to Kubernetes service](https://docs.microsoft.com/en-us/azure/aks/kubernetes-action)  | [Recording](https://www.youtube.com/watch?v=iRNfeZSkn5Y&ab_channel=MicrosoftReactor)   |

### [Streamlining database and ML deployments using GitHub Actions](https://www.meetup.com/microsoft-reactor-bengaluru/events/279015454/)

* Deploying Machine Learning app using GitHub Actions 
* Deploying databases changes using GitHub Actions 

|     Source Code     |    Reference    | Video |
|     :---    | :---           | :---:       |
| [GitHub repo - Azure Machine Learning](https://github.com/vivsridh4/azureml-githubactions)<br/>[GitHub repo - Azure databases](https://github.com/vivsridh4/azure-database-githubactions) | [Use GitHub Actions with Azure Machine Learning](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-github-actions-machine-learning)<br/>[Quickstart: Create an Azure Database for MySQL server by using the Azure portal](https://docs.microsoft.com/en-us/azure/mysql/quickstart-create-mysql-server-database-using-azure-portal)<br/>[Quickstart: Use GitHub Actions to connect to Azure MySQL](https://docs.microsoft.com/en-us/azure/mysql/quickstart-mysql-github-actions)  | [Recording](https://www.youtube.com/watch?v=DwWsJwG5-KE&t=2297s&ab_channel=MicrosoftReactor)   |

### [Implementing container scanning and accelerating development with GitHub Actions](https://www.meetup.com/microsoft-reactor-bengaluru/events/279015477/)

* Infra as code using GitHub actions
* Container scanning
* Accelerating development via visual studio extension & CLI

|     Source Code     |    Reference    | Video |
|     :---    | :---           | :---:       |
| [GitHub repo - Container Scanning](https://github.com/vivsridh4/containerscan)<br/>[GitHub repo - Azure ARM Templates](https://github.com/vivsridh4/deploy_arm_template) | [Deploy ARM templates by using GitHub Actions](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/deploy-github-actions)<br/>[Container Scanning](https://github.com/Azure/container-scan)<br/>[Manage Azure Policies with GitHub](https://docs.microsoft.com/en-in/azure/developer/github/manage-azure-policy) | [Recording](https://www.youtube.com/watch?v=A3ubK3oMhg8&t=2179s&ab_channel=MicrosoftReactor)   |

### :evergreen_tree: Hacks

:seedling: **Hack - 01:** Build & Deploy a non container app to App Service using GitHub Actions (choose any of your favourite language).

:seedling: **Hack - 02:** Deploy a new version and direct a part of the traffic to the new version on Azure Kubernetes Service (using Github Actions); you need to set a percentage action input to control the traffic split; i.e, a percentage of your users will use the new version.

:seedling: **Hack - 03:** Build & Deploy a Java function app to Azure Functions using GitHub Actions.

:seedling: **Hack - 04:** Use any of the Azure community policy with GitHub Actions. Find all community policy here - [Polices Repo](https://github.com/Azure/Community-Policy/tree/master/Policies)

:seedling: **Hack - 05:** Run a training on Azure Machine Learning and get status of pipelines & publish pipeline endpoint using "output" workflow command.















