# linux-module
linux modules 

## How to compile
`make` 

## How to compile new modules
1. Create a new Module
2. Add these to Makefile `obj-m+= "your-module-name.o"`
3. `$ make`

## How to load module in kernel
`insmod "your-module-name.ko"`

## How to remove module from Kernel
`rmmod "your-kernel-name.ko"`

## List of all the Modules in Kernel
`lsmod`

## How to contribute

- Fork the project on github.
- Create a module branch.
- Please keep PR titles easy to read and descriptive of changes, this will make them easier to merge.
- Pull requests must be made against development branch. Any other branch (unless specified by the maintainers) will get rejected.
- Have **fun!**

## Authors
* **Rahul Tuteja**  - [doomers](https://github.com/doomers) 

## License
This linux modules is open-sourced software licensed under the [Apache License](LICENSE).
