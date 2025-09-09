# spresense-sdk-template

Clone [sonydevworld/spresense](https://github.com/sonydevworld/spresense) repository and place this repository directory in its root.

```
|-- sdk
|-- this template
    |-- app       ... Add your application
```

configuration:

```bash
cd ../sdk
tools/config.py default
tools/config.py -m # Make your App configurations
```

build with Make:

```bash
cd ../sdk
make
```

burn to SPRESENSE:

```bash
cd ../sdk
tools/flash.sh -c <YOUR_PORT> nuttx.spk
```
