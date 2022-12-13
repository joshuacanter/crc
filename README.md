## Quick setup for new OCP instances

To setup an instance with stated operators, use

` oc apply -k bootstrap/overlays/<server>/ `

Currently the I have the following configs:




## Background
Inspired by the examples from Christian Hernandez in [The Path to GitOps](https://developers.redhat.com/e-books/path-gitops) and the related [GitHub account](https://github.com/christianh814/example-openshift-go-repo).



## Troubleshooting

If you have installed multiple times and keep getting errors about the Catalog source, the best way to fix is to delete and reinstall both the subscription and the csv:

https://access.redhat.com/solutions/6603001