% Conquering Linux
% Robin McCorkell
% 2017-01-25

# Setup Instructions

# Getting Started

Make sure you have:

* VirtualBox installed
* Arch Linux ISO downloaded
* A few slices of pizza next to you :)

# Setting up a VM

## Virtual Machines

For those unfamiliar, a VM is:

* A way to run other OSes on your machine
* A way to segregate resources
* A place to break things with no consequences

## Create the VM

* Type: Linux, Arch Linux (64-bit)
* RAM: 1024MB is fine, more if you can spare
* Storage: Dynamically allocated, 8GB
* In settings:
    - System -> Motherboard -> Enable EFI (important!)

## Booting into the Arch ISO

* Click on the VM, press Start
* Select start-up disk: find your downloaded ISO
* Wait a bit (eat pizza?)
* `root@archiso ~ #`