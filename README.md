# CPU temperature exporter for prometheus
This exporter is tested on Proxmox (version 6.2)

For the record, I am running it on Gigabyte x570 Aorus Elite and Ryzen 5 3600.

It makes use of the `sensors` utility which is showing the CPU sensor as a PCI adapter.

To adapt the script to a differend hardware/software configuration, the output parsing might need to be changed.
