# AI Software Template

This application, test-codegen, is created from an AI Software Template. These software templates create a new source code repository as well as a new GitOps deployment repository.

The chosen sample source applicable is included in the source code repository.

## Sample Source Application

A Large Language Model (LLM)-enabled streamlit code generation application. This specialized bot helps with code related queries.

## Repositories

The source code for your application can be found in [https://github.com/fpetk/test-codegen-helm ](https://github.com/fpetk/test-codegen-helm ).
 
The GitOps repository, which contains the Kubernetes manifests for the application can be found in 
[https://github.com/fpetk/test-codegen-helm-gitops ](https://github.com/fpetk/test-codegen-helm-gitops ). 

## Application namespaces 

The default application is found in the namespace: **`rhdh-app`**. Applications can be deployed into their own unique namespace or multiple software templates can generate numerous applications into the same namespace.