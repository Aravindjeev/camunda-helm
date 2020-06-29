# camunda-helm
Camnunda is a complete process automation tech stack with powerful execution engines for BPMN workflows and DMN decisions paired with essential applications for modeling, operations and analytics.

## Chart Details
This chart contains latest image of camunda from official docker repository camunda/camunda-bpm-platform. 
This chart provide NodePort servictype and doesn't provide a backend DB.

## Installing the Chart
Clone the repository
```bash
$ git clone https://github.com/Aravindjeev/camunda-helm
```
To install the chart with the helm release name `my-release`:
```bash
$ helm install --name my-release camunda-helm --namespace camunda
```
Verify deployment
```bash
$ kubectl get pods --namespace camunda
```
