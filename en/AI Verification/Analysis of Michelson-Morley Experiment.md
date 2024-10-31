In the drag ether hypothesis, it is assumed that the ether on Earth rotates synchronously with the Earth, i.e., is stationary relative to the Earth. In this scenario, if we wish to perform the Michelson-Morley experiment on an airplane moving at a speed of 800 m/s and detect changes in interference fringes due to the ether wind, we need to calculate the minimum optical path length required.

### Experimental Setup and Basic Assumptions

- **Light Source**: Provides monochromatic light.
- **Beam Splitter**: Divides the incident light into two beams; one travels vertically (longitudinal arm), the other horizontally (transverse arm).
- **Mirrors**: Two high-precision mirrors placed in the vertical and horizontal directions from the beam splitter.
- **Detector**: Observes the interference fringes after the two beams recombine.
- **Plane Speed**: $(v = 800 \, \text{m/s} )$
- **Speed of Light**: $(c = 3 \times 10^8 \, \text{m/s} )$
- **Frequency of Light**: $(f = 5 \times 10^{14} \, \text{Hz} )$ (corresponding to a sodium light wavelength of 589 nm)

### Transverse Arm (Perpendicular to Plane's Movement)

- **Outward Journey**: Light travels from the beam splitter to the mirror.

  - Time $(t_1 = \frac{L}{\sqrt{c^2 - v^2}} )$
  - Frequency change: $(f_1 = f \left( \frac{c - v}{c} \right) )$
- **Return Journey**: Light returns from the mirror to the beam splitter.

  - Time $(t_2 = \frac{L}{\sqrt{c^2 - v^2}} )$
  - Frequency change: $(f_2 = f \left( \frac{c + v}{c} \right) )$

Total time $(T_{\perp})$ is:

$$
[ T_{\perp} = t_1 + t_2 = \frac{2L}{\sqrt{c^2 - v^2}} ]
$$

Total phase change $(\Delta \phi_{\perp})$ is:

$$
[ \Delta \phi_{\perp} = 2\pi f_1 t_1 + 2\pi f_2 t_2 ]
$$

$$
[ \Delta \phi_{\perp} = 2\pi f \left( \frac{c - v}{c} \right) \frac{L}{\sqrt{c^2 - v^2}} + 2\pi f \left( \frac{c + v}{c} \right) \frac{L}{\sqrt{c^2 - v^2}} ]
$$

$$
[ \Delta \phi_{\perp} = 2\pi f \cdot \frac{L}{\sqrt{c^2 - v^2}} \left( \frac{c - v}{c} + \frac{c + v}{c} \right) ]
$$

$$
[ \Delta \phi_{\perp} = 2\pi f \cdot \frac{L}{\sqrt{c^2 - v^2}} \cdot \frac{2c}{c} ]
$$

$$
[ \Delta \phi_{\perp} = 4\pi f \cdot \frac{L}{\sqrt{c^2 - v^2}} ]
$$

### Longitudinal Arm (Along the Plane's Movement)

- **Outward Journey**: Light travels from the beam splitter to the mirror.

  - Time $(t_1 = \frac{L}{c - v} )$
  - Frequency change: $(f_1 = f \left( \frac{c - v}{c} \right) )$
- **Return Journey**: Light returns from the mirror to the beam splitter.

  - Time $(t_2 = \frac{L}{c + v} )$
  - Frequency change: $(f_2 = f \left( \frac{c + v}{c} \right) )$

Total time $(T_{\parallel})$ is:

$$
[ T_{\parallel} = t_1 + t_2 = \frac{L}{c - v} + \frac{L}{c + v} ]
$$

$$
[ T_{\parallel} = L \left( \frac{1}{c - v} + \frac{1}{c + v} \right) ]
$$

$$
[ T_{\parallel} = L \left( \frac{(c + v) + (c - v)}{(c - v)(c + v)} \right) ]
$$

$$
[ T_{\parallel} = L \left( \frac{2c}{c^2 - v^2} \right) ]
$$

$$
[ T_{\parallel} = \frac{2Lc}{c^2 - v^2} ]
$$

Total phase change $(\Delta \phi_{\parallel})$ is:

$$
[ \Delta \phi_{\parallel} = 2\pi f_1 t_1 + 2\pi f_2 t_2 ]
$$

$$
[ \Delta \phi_{\parallel} = 2\pi f \left( \frac{c - v}{c} \right) \frac{L}{c - v} + 2\pi f \left( \frac{c + v}{c} \right) \frac{L}{c + v} ]
$$

$$
[ \Delta \phi_{\parallel} = 2\pi f \cdot \frac{L}{c} + 2\pi f \cdot \frac{L}{c} ]
$$

$$
[ \Delta \phi_{\parallel} = 4\pi f \cdot \frac{L}{c} ]
$$

### Phase Difference Superposition

The total phase difference $(\Delta \phi)$ is:

$$
[ \Delta \phi = \Delta \phi_{\parallel} - \Delta \phi_{\perp} ]
$$

$$
[ \Delta \phi = 4\pi f \cdot \frac{L}{c} - 4\pi f \cdot \frac{L}{\sqrt{c^2 - v^2}} ]
$$

$$
[ \Delta \phi = 4\pi f L \left( \frac{1}{c} - \frac{1}{\sqrt{c^2 - v^2}} \right) ]
$$

### Approximate Treatment

Using Taylor expansion approximation:

$$
[ \frac{1}{\sqrt{c^2 - v^2}} \approx \frac{1}{c} \left( 1 + \frac{v^2}{2c^2} \right) ]
$$

Substitute the approximate value:

$$
[ \Delta \phi \approx 4\pi f L \left( \frac{1}{c} - \frac{1}{c} \left( 1 + \frac{v^2}{2c^2} \right) \right) ]
$$

$$
[ \Delta \phi \approx 4\pi f L \left( \frac{1}{c} - \frac{1}{c} - \frac{v^2}{2c^3} \right) ]
$$

$$
[ \Delta \phi \approx 4\pi f L \left( -\frac{v^2}{2c^3} \right) ]
$$

$$
[ \Delta \phi \approx -\frac{2\pi f L v^2}{c^3} ]
$$

### Observable Interference Phenomenon

To produce an observable interference phenomenon, the phase difference $(\Delta \phi)$ should be at least an integer multiple of $(2\pi)$. Let $(\Delta \phi = 2\pi n)$, where $(n)$ is an integer.

$$
[ -\frac{2\pi f L v^2}{c^3} = 2\pi n ]
$$

$$
[ -\frac{f L v^2}{c^3} = n ]
$$

$$
[ L = -\frac{n c^3}{f v^2} ]
$$

For the plane's speed $(v = 800 \, \text{m/s} )$ and the frequency of light $(f = 5 \times 10^{14} \, \text{Hz} )$, we get:

$$
[ L = -\frac{n (3 \times 10^8 \, \text{m/s})^3}{(5 \times 10^{14} \, \text{Hz}) (800 \, \text{m/s})^2} ]
$$

$$
[ L = -\frac{n (27 \times 10^{24})}{(5 \times 10^{14}) (6.4 \times 10^5)} ]
$$

$$
[ L = -\frac{n (27 \times 10^{24})}{3.2 \times 10^{20}} ]
$$

$$
[ L = -\frac{n \times 27}{3.2} \times 10^4 \, \text{m} ]
$$

$$
[ L \approx -8.44n \times 10^4 \, \text{m} ]
$$

$$
[ L \approx -84400n \, \text{m} ]
$$

Since $(L)$ must be positive, take $(n = -1)$ (or any negative integer), we get:

$$
[ L \approx 84400 \, \text{m} ]
$$

### Conclusion

Based on the above calculations, in the drag ether hypothesis, if one wishes to perform the Michelson-Morley experiment on an airplane moving at a speed of 800 m/s and detect changes in interference fringes due to the ether wind, the minimum optical path length required is approximately 84,400 meters (about 84.4 kilometers).

### Practical Results

This result shows that even under the drag ether hypothesis, the required optical path length is extremely large, far exceeding the lengths achievable in actual experiments. This further explains why no expected changes in interference fringes were observed in the real Michelson-Morley experiment, supporting the principle of the constancy of the speed of light in special relativity.
