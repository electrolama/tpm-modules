Chip: [Infineon Optiga SLB 9670 TPM2.0](https://www.infineon.com/cms/en/product/security-smart-card-solutions/optiga-embedded-security-solutions/optiga-tpm/slb-9670vq2.0/)

Order codes:
SLB9670VQ20FW785XTMA1 (standard temp. range)
SLB9670XQ20FW785XUMA1 (extended temp. range)

Both options work. Package: PG-VQFN-32-13

Chip supply 1.8V or 3.3V, do not use with a 5V header (if that exists?)

Pinout taken from the user manual for ASUS PRIME B550-PLUS motherboard ([E16536_PRIME_B550-PLUS_UM_WEB_051420.pdf](https://dlcdnets.asus.com/pub/ASUS/mb/SocketAM4/PRIME_B550-PLUS/E16536_PRIME_B550-PLUS_UM_WEB_051420.pdf)). Pins highlighted in green are **educated guesses** for the ones used by the SPI-TPM module from ASUS.

**Important Note**: This module is meant to be installed in the *opposite* orientation as the ASUS module, as in the body of this module should face the CPU cooler, with the component side facing outwards. Unfortunately this module might clash with your cooler, this is untested at this moment. Module is designed this way because routing a super compact board would be very difficult and beyond my current abilities at this moment.
