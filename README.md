# brooklyn-bash-completion

A Bash auto-completion script for the br command.

Copy the [br](br) file to your `/etc/bash_completion.d` directory (or local equivalent) to enable
auto-completion of Brooklyn CLI commands.

Currently supported completions:

- `br application APPID`
- `br application APPID entity ENTITYID`
- `br application APPID sensor SENSOR`
- `br application APPID effector EFFECTOR`
- `br application APPID config CONFIG`
- `br application APPID entity ENTITYID sensor SENSOR`
- `br application APPID entity ENTITYID effector EFFECTOR`
- `br application APPID entity ENTITYID config CONFIG`
- `br deploy *.yaml`
- `br add-catalog *.bom`

## Getting Started

Install the script using the following commands:

```shell
% wget https://raw.githubusercontent.com/brooklyncentral/brooklyn-bash-completion/master/br
% sudo mv br /etc/bash_completion.d/br
% . /etc/bash_completion.d/br
```
