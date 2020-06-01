# Hybrid cloud technologies

Technologies that brings serverless to any cloud, public, on premise.

|Name|Depends on|Features|
|----|--------|--------------|
|Knative|Kubernetes, Service Mesh (Istio, Kourier)|Autoscaled (0 to n) services, Blue vs Green deployment, Eventing system, Any runtime, FaaS support (near future)|

* Apache OpenWhisk
* OpenFaas

# FaaS Platforms

|Name|Runtimes|Custom Runtime|
|----|--------|--------------|
|AWS Lambda|nodejs12.x, nodejs10.x, python3.8, python3.7, python3.6, python2.7, ruby2.7, ruby2.5, java11, java8, go1.x, dotnetcore3.1, dotnetcore2.1| Y|
|Google Cloud Functions| Node.js 8, Node.js 10, Python, Go, Java| N|
|Microsoft Azure Functions| .Net Core 3.1, Node 10, Node 12, Java 8, PowerShell Core 6, Python 3.6, Python 3.7, Python 3.8, TypeScript| Y(in preview) |
|IBM Cloud Functions| Nodejs 10.15, Python 3.6, Python 3.7, Swift 4.2, PHP 7.3, Go 1.11, Java 8, Ruby 2.5, .Net Core 2.2| Y(via Docker)|
|Alibaba Function Compute | Node.js 6, Node.js 8, Node.js 10, PHP 7.2, Python 2.7, Python 3, .Net Core 2.1, Java 8| Y |

* Cloudflare workers
* netlify functions
* vercel

# Databases

## NoSQL
* Fauna
* Dynamo

## SQL
* AWS Aurora Serverless
* Azure SQL Database serverless

# Monitoring, tracing and alerting
* Dashbird
* Epsagon

# IaaC
* Terraform
* AWS CDK
* AWS SAM
* Serverless Framework
* Pulumi
