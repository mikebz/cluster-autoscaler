# cluster-autoscaler

## Description
Sample that shows how to use a setter to set the cluster name for cluster-autoscaler.

## Usage

### Fetch the package
`kpt pkg get https://github.com/mikebz/cluster-autoscaler cluster-autoscaler`
Details: https://googlecontainertools.github.io/kpt/reference/pkg/get/

### View package content
`kpt cfg tree cluster-autoscaler`
Details: https://googlecontainertools.github.io/kpt/reference/cfg/tree/

### List setters
`kpt cfg list-setters cluster-autoscaler`
Details: https://googlecontainertools.github.io/kpt/reference/cfg/list-setters/

### Set a value
`kpt cfg set cluster-autoscaler cluster_name my-cluseter`
Details: https://googlecontainertools.github.io/kpt/reference/cfg/set/

### Apply the package
```
kpt live init cluster-autoscaler
kpt live apply cluster-autoscaler --reconcile-timeout=2m --output=table
```
Details: https://googlecontainertools.github.io/kpt/reference/live/
