# MaxGainTransistorMatch
Script to calculate reflection coefficients for maximum transistor amplifier gain using S parameters.

Add the s parameters for your transistor amplifier circuit to the script and it will calculate the rollet's stability factor as well as the source and load reflection co-efficients for maximum gain.

NOTE: This script is for the bilateral case (s12 != 0 ) and is only recommended if the amplifier is unconditionally stable at the design frequency. The equations implemented can be found in Pozar - Microwave Engineering: chapter 12.3.
