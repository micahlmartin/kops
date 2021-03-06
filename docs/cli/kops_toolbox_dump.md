
<!--- This file is automatically generated by make gen-cli-docs; changes should be made in the go CLI command code (under cmd/kops) -->

## kops toolbox dump

Dump cluster information

### Synopsis

Displays cluster information.  Includes information about cloud and Kubernetes resources.

```
kops toolbox dump [flags]
```

### Examples

```
  # Dump cluster information
  kops toolbox dump --name k8s-cluster.example.com
```

### Options

```
  -h, --help            help for dump
  -o, --output string   output format.  One of: yaml, json (default "yaml")
```

### Options inherited from parent commands

```
      --alsologtostderr                  log to standard error as well as files
      --config string                    yaml config file (default is $HOME/.kops.yaml)
      --log_backtrace_at traceLocation   when logging hits line file:N, emit a stack trace (default :0)
      --log_dir string                   If non-empty, write log files in this directory
      --logtostderr                      log to standard error instead of files (default false)
      --name string                      Name of cluster. Overrides KOPS_CLUSTER_NAME environment variable
      --state string                     Location of state storage (kops 'config' file). Overrides KOPS_STATE_STORE environment variable
      --stderrthreshold severity         logs at or above this threshold go to stderr (default 2)
  -v, --v Level                          log level for V logs
      --vmodule moduleSpec               comma-separated list of pattern=N settings for file-filtered logging
```

### SEE ALSO

* [kops toolbox](kops_toolbox.md)	 - Misc infrequently used commands.

