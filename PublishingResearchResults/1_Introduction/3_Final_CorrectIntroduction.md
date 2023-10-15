# Introduction correction

The conversion of AC to DC power by electronic converters introduces various issues affecting power quality. These include harmonic distortions, voltage fluctuations, poor power factor, voltage imbalances, electromagnetic interference, and resonance problems. These problems occur at the "point of common coupling" (PCC), where multiple electrical circuits connect, and may ultimately lead to a lower-quality power supply for end consumers, with potential disruptions for their electrical equipment.

This issue can be compensated by using the filters at the front end of AC/DC converter [1]. However, filters that meet the power quality requirements are not an economical solution [2]. The alternative solution to above problem is modification of the converter (HPFC) to meet power quality requirements [3]. In the last decade, many converter designs have been proposed, like HB[4], FCC [5] or DCC [6], all extensively used in medium voltage and high power applications such as variable-speed control of AC drives [7], HVDC transmission, FACTS [8], static VAR compensation [9], battery storage systems, etc. 

One popular AC/DC converter that solves this problem is the MPC structured converter.

This paper is focused on the 5-level Diode Clamped Converter (5LDCC), an MPC structured converter that applies very well to reactive power transfer. This improvement is not without drawbacks, since it shows capacitor voltage balancing problems when used for active power transfer applications, especially at high modulation indexes with UPF operation between utility and DC link capacitors.


 