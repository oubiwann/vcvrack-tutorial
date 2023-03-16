# VCV Rack Module Development

This is the example module documented in [this tutorial](https://vcvrack.com/manual/PluginDevelopmentTutorial) (with a few minor changes).

For plugin development on systems an Apple M1 chip, I've found that all I need to do to compile the plugin such that it will be loaded by my VCV Rack installation is start a bash session with this:

```shell
arch -x86_64 /bin/bash
```
