## This is a alpha stage project. Use it with your own risk. 

To install the cli tool just execute the command below. 

```bash
curl -sSL https://api.onkube.io/dl | sh
```

Just call the command to see how to use. 

```bash

❯ onkube
onkube.com CLI application.
Manage your deployment simply over your terminal.

Usage:
  onkube [command]

Available Commands:
  help        Help about any command
  login       Login to onkube.com
  logout      Login to onkube.com
  ls          List Deployments
  new         Create a new deployment
  register    Register to onkube.com
  version     Print the version number of onkube

Flags:
  -h, --help   help for onkube

Use "onkube [command] --help" for more information about a command.


```

1. Register with ```onkube register``` if you don't have an account.
2. Login with ```onkube login```.

Now you can create ex. metabase just with the following command. 

```bash
onkube new metabase
```

for now, only metabase is available. 

Have fun. 


