# Deployment

This section contains scripts for deploying your trained model in various ways. We currently support the following deployment methods:

| Method | Description |
| :--- | :--- |
| [Edge](deployment/edge/) | For deploying models on edge devices such as Raspberry Pi & NVIDIA Jetson. |
| [Inference API](deployment/inference-api/) | Where models are hosted on our servers and inference can be performed through API calls. |
| [Local Inference](deployment/local-inference/) | For running simple inference scripts on your local machine. |

## Getting Started

Please refer to the `README.md` file in each folder for more information on how to use the scripts.
## Download Model

Users can download their trained model directly from [Nexus](https://nexus.datature.io/) or port the trained model through Datature Hub. Users need two sets of keys for the second method: `Model Key` and `Project Secret Key`.<br>

### Model Key

To convert that artifact into an exported model for the prediction service, in Nexus, select `Artifacts` under Project Overview. Within the artifacts page, select your chosen artifact and model format to generate a model key for deployment by clicking the triple dots box shown below.

![modelkey](/assets/modelkey.png)

### Project Secret Key

You can generate the project secret key on the Nexus platform by going to `API Management` and selecting the `Generate New Secret` button, as shown below.

![projectsecret](/assets/projectsecret.png)
