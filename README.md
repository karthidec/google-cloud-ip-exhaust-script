# google-cloud-ip-exhaust-script

## IP Exhaust:
In Google Cloud Platform (GCP), "IP exhaust" typically refers to the scenario where the available IP address space within a Virtual Private Cloud (VPC) network is depleted, preventing the creation of new network resources, such as VM instances, Pods, or services.


## Automating IP Exhaust Analysis in Google Cloud

One of the common challenges in large-scale cloud environments is IP exhaustion — when your VPC subnet runs out of available IPs, blocking new instances, services, or Pods from being created. To help the SRE team stay ahead, I built a small automation that combines gcloud, Python, and jq to dynamically gather and visualize IP allocation percentages across all VPC networks. This simple script now provides quick visibility into IP usage trends, enabling us to proactively manage subnet capacity before issues arise. Automation remains a core component of our efforts to enhance observability. 

