# Epson EcoTank cleaner

Cleaning the print nozzles of an Epson EcoTank 2710 from Linux

![BK YMC pattern](pattern.webp)


> This bash script allows you to check and clean the print heads of an Epson EcoTank 2710 printer accessible via network (USB not supported).
> The data sent to the printer was collected using `tshark` tool (listening to the Epson utility installed on Windows).
> Tests have only been performed on the 2710 model : _please let me know via a [new issue](https://github.com/patatetom/ecotankcleaner/issues/new/choose) if the script works on another model ;-)_


## Installation

- download `ecotankcleaner` bash script :
> `wget  -O ~/.local/bin/ecotankcleaner  https://raw.githubusercontent.com/patatetom/ecotankcleaner/main/ecotankcleaner`
> or
> `curl  https://raw.githubusercontent.com/patatetom/ecotankcleaner/main/ecotankcleaner  >  ~/.local/bin/ecotankcleaner`
- check his simple code :
> `less  ~/.local/bin/ecotankcleaner`
- make it executable :
> `chmod  +x  ~/.local/bin/ecotankcleaner`
- run it :
> `ecotankcleaner  LanName_or_IpAddress`


## Compatibility

- Epson EcoTank 2710
