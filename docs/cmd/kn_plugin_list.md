## kn plugin list

List plugins

### Synopsis

List all installed plugins.

Available plugins are those that are:
- executable
- begin with "kn-"
- Kn's plugin directory
- Anywhere in the execution $PATH

```
kn plugin list
```

### Options

```
  -h, --help      help for list
      --verbose   verbose output
```

### Options inherited from parent commands

```
      --cluster string      name of the kubeconfig cluster to use
      --config string       kn configuration file (default: ~/.config/kn/config.yaml)
      --context string      name of the kubeconfig context to use
      --kubeconfig string   kubectl configuration file (default: ~/.kube/config)
      --log-http            log http traffic
```

### SEE ALSO

* [kn plugin](kn_plugin.md)	 - Manage kn plugins

