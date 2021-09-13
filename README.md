# PH315-52OC072
Customizations:
- ADATA SX6000PNP 1TB nvme
- BIOS_Acer_1.10_A_A
  - Do not upgrade the bios further than this, at least with adata nvme, won't boot.
  - In order to upgrade the bios, let it with the standard hardware only (remove the second nvme), otherwise you will only be able to enter the bios once and gill give you flashing cursor as if wrong password entered too many times.
  
  In orer to ypgrade the bios:
  - Shut down, remove any extra hardware, mainly the second nvme.
  - Proceed with the bios upgrade under windows.
  - Enter the bios and set back AHCI (required to be able to boot ubuntu or Mac).
  - Now you can shut down again and re-install all harware, this way you will have the bios properlly flashed and will be able to enter it as many times as required.
