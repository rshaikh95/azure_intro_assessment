## Azure Intro Assessment

### Storage: 

## A.	Access tiers for blob data

This service archives and organizes data based on how frequently it will be accessed and how long it will be retained. Azure storage offers different tiers based on how it is being used. Hot tier is an online tier optimized to store data that is used and modified frequently. Cool tier is also online and is for storing data that is infrequently accessed or modified. Data is stored for 30 days; cold tier’s data is stored for 90 days. Archive data is an offline tier stored for 180 days. The storage costs are higher on the hotter tiers and lower on colder tiers and vice versa for access costs.

An SDK can be used to leverage this service through Python 3.6+. By creating and installing a pip package for azure storage through Python, it is possible to run an Azure Blob Storage client library. This allows the user to store unstructured data through an account which contains containers with blobs to categorize and organize unstructured data. A container can be a type of category which contains data referenced as blobs in the client service. 

## B.	Microsoft Azure confidential ledger (ACL)

ACL is a secure service for managing sensitive data records. It runs on hardware-backed secure enclaves which keep attacks limited. It also uses a trusted computing base which ensures confidentiality. Business transactions, admin control and changes and security events for IT can be stored on the ledger. 

The ledger uses REST APIs which can be integrated into applications. Administrative and Functional APIs can be used to manage the data in the ledger. The ledger can be run through Python using an Azure SDK. The user can install the packages into a Python environment for the Azure Active Directory and then install the specific confidential ledger packages. 

### Compute: 

## A.	Azure App Service

Enables users to build and host apps, mobile back ends and RESTful APIs in multiple programming languages. It offers auto-scaling and supports both Windows and Linux with deployments from GitHub. The Azure App Service is fully managed and includes many features.
The quick start can be downloaded using git clone and then run locally. The service can then be used to host a user’s application using Azure CLI and then deployed to GitHub. 

## B.	Azure Functions

Azure Functions is a cloud service available anytime that provides continuous updated infrastructure and resources for apps. It provides serverless compute for Azure. Functions allow users to build web APIs, respond to database changes, process IoT streams, and manage message queues. 

Azure Functions can be run via a Visual Studio Code IDE or through Python 3.7, 3.8 and 3.9 which are supported by Azure Functions. Using a .venv command can create a virtual environment in the shell. 

### Database Services: 

## A.	Azure SQL database documentation

It is a fully managed platform as a service database engine that handles most of the functions such as upgrading, patching, backups and monitoring without user involvement. Azure SQL Database can create data storage layer for applications and solutions in Azure. There are different models that can be purchased based on the amount of memory and speed of storage required. 

A GitHub repo can be made with a dacpac package which can be deployed in the Azure shell using Python language. This can be brought back to GitHub to review. 

## B.	Azure Cache for Redis Documentation

Azure Cache is a memory data storage for Redis software. Redis improves performance and scalability of an app that uses data stores heavily. It processes large volumes of application requests by keeping data that is frequently used in the memory to read and write to quickly. It can be used to distribute data, store a session, messaging broker and more. 

A resource is first created in Azure and then a cache which is then connected to the Redis server using host name, ports, and access keys from the Azure Portal. Using the interface Redis-py and the Python package tool pip, users can install the package. This will allow users to read and write to the cache
