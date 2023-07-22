# QA403 Impedance Fixture

A test fixture for the QuantAsylum QA403 for measuring impedance based on Matt's blog posts:
* https://quantasylum.com/blogs/news/speaker-impedance-measurements
* https://quantasylum.com/blogs/news/measuring-input-impedance

![PCB only](https://github.com/excitonlabs/QA403-Impedance-Fixture/blob/master/Images/naked.jpg?raw=true)

The PCB is fairly flexible, there are three footprints for SMD currents sense resistors and a single through-hole footprint. These are in parallel so the expectation is you place one and write the value on the silk screen space provided. The PCB also had an additional BNC for the L- input which may be useful in push-pull differential measurements.

## Questions

Forum post https://forum.quantasylum.com/t/comments-welcomed-on-test-fixture-pcb-for-impedance-measurements

## How to get this PCB

0. Wait until I confirm everything works (PCBs will arrive this week).
1. Order PCBs from a fab. house such as https://jlcpcb.com or email me I have may spare ones.
2. Order components from the BOM

## BOM

See datasheets in `/Parts` directory.

* Optional 2 x [MKDSN 1,5/ 2-5,08 1729128, terminal block](https://www.phoenixcontact.com/en-us/products/printed-circuit-board-terminal-mkdsn-15-2-508-1729128)
* Optional 2 x [Neutrik NMJ6HCD2, Jack socket](https://www.neutrik.com/en/product/nmj6hcd2)
* 4  x [TE Connectivity 5221123-2, BNC socket](https://www.te.com/usa-en/product-5221123-2.html)
* 1 x current sense resistor of the following types:
  * 2012 (5025)
  * 1206 (3216)
  * 0805 (2012)
  * Through-hole 

## Examples

![PCB with jack sockets](https://github.com/excitonlabs/QA403-Impedance-Fixture/blob/master/Images/jacks.jpg?raw=true)
![PCB with terminals](https://github.com/excitonlabs/QA403-Impedance-Fixture/blob/master/Images/terminals.jpg?raw=true)
![PCB's back](https://github.com/excitonlabs/QA403-Impedance-Fixture/blob/master/Images/back.jpg?raw=true)
