# onboarding.sh


The 2 scripts are taken from https://console.cast.ai/api/v1/scripts/aks/onboarding.sh

We divided the global script above into 2 parts targetting different personas:
- onboarding_azure.sh contains everything related to azure configuration
- onboarding_k8s.sh contains everything related to castai deployments on the k8s cluster

Please update the variables where you see "ToBeDefined"

Then run:
````
chmod +x onboarding_azure.sh
./onboarding_azure.sh
````
 
(disclaimer: Scripts are my own and are provided without support)
