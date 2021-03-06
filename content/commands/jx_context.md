---
date: 2019-01-22T09:44:30Z
title: "jx context"
slug: jx_context
url: /commands/jx_context/
---
## jx context

View or change the current Kubernetes context (Kubernetes cluster)

### Synopsis

Displays or changes the current Kubernetes context (cluster).

```
jx context [flags]
```

### Examples

```
  # to select the context to switch to
  jx context
  
  # or the more concise alias
  jx ctx
  
  # view the current context
  jx ctx -b
  
  # Change the current namespace to 'minikube'
  jx ctx minikube
```

### Options

```
  -b, --batch-mode                In batch mode the command never prompts for user input
  -f, --filter string             Filter the list of contexts to switch between using the given text
      --headless                  Enable headless operation if using browser automation
  -h, --help                      help for context
      --install-dependencies      Should any required dependencies be installed automatically
      --log-level string          Logging level. Possible values - panic, fatal, error, warning, info, debug. (default "info")
      --no-brew                   Disables the use of brew on macOS to install or upgrade command line dependencies
      --pull-secrets string       The pull secrets the service account created should have (useful when deploying to your own private registry): provide multiple pull secrets by providing them in a singular block of quotes e.g. --pull-secrets "foo, bar, baz"
      --skip-auth-secrets-merge   Skips merging a local git auth yaml file with any pipeline secrets that are found
      --verbose                   Enable verbose logging
```

### SEE ALSO

* [jx](/commands/jx/)	 - jx is a command line tool for working with Jenkins X

###### Auto generated by spf13/cobra on 22-Jan-2019
