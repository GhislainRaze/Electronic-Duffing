# An electronic Duffing oscillator

## Overview
This repository contains files for the realization of an electronic Duffing oscillator, i.e., a circuit which simulates Duffing's equation

$\qquad m\ddot{x}(t) + c\dot{x}(t) + kx(t) + k_3 x^3(t) = f_{ext}(t),$
    
with $m>0$, $c\geq0$ and $k_3\geq0$.

The circuit takes a signal proportional to $f_{ext}$ as input and outputs signals proportional to $x$ and $\dot{x}$. It allows for tunable values of the parameters $c$, $k$ and $k_3$ via the use of potentiometers. It is also possible to chose positive or negative values for $k$ and obtain a single- or double-well oscillator, respectively.

The circuit requires an external power source with symmetric supplies. The input and output signals can be imposed/measured with BNC connectors.

## References

The circuit diagrams were realized using KiCad7.0 (https://www.kicad.org/), inspired from the following works:

\[1\] B. K. Jones and G. Trefan, “The Duffing oscillator: A precise electronic analog chaos demonstrator for the undergraduate laboratory,” Am. J. Phys., vol. 69, no. 4, pp. 464–469, Apr. 2001, doi: [10.1119/1.1336838](https://doi.org/10.1119/1.1336838).

\[2\] K. Srinivasan, K. Thamilmaran, and A. Venkatesan, “Effect of nonsinusoidal periodic forces in Duffing oscillator: Numerical and analog simulation studies,” Chaos, Solitons & Fractals, vol. 40, no. 1, pp. 319–330, Apr. 2009, doi: [10.1016/j.chaos.2007.07.090](https://doi.org/10.1016/j.chaos.2007.07.090).

## More information

For more infomation, see the [documentation file](DOC/Electronic_Duffing.pdf).

## License

<p xmlns:cc="http://creativecommons.org/ns#" >This work is licensed under <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"></a></p>

## Disclaimer

It is believed by the author that the design does not violate the Copyright of any other party. This cannot be guaranteed however, and the author accepts no liability for loss or damages that may be imposed upon the user by any Court of Law, statutory or other body, should it transpire that a similar circuit has been simultaneously or previously designed, published or patented by another party.

The author cannot be held responsible for any issues or damages either to life or property, or as monetary or physical losses, that might occur during the use of this circuit, either due to negligence, ignorance or lack of proper knowledge about the subject. It is entirely the user’s responsibility to determine the suitability of this design for the intended purpose, and to take enough precautions before assembling and using the circuit.
