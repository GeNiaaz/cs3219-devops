# cs3219-devops

### To run locally

Set service's spec.type to `NodePort`

Otherwise, use `ClusterIP`

Run this to get info: `kubectl get all -n cs3219`

### Postman commands ==============

#### GET order

Run localhost:<port_number>/orders

#### GET customer

Run localhost:<port_number>/customers

#### GET catalog

Run localhost:<port_number>/catalogs
