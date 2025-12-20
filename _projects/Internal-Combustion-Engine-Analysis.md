---
layout: project
title: Internal Combustion Engine Analysis
description: Analysis of the components, properties, and efficieny of an internal combustion engine
technologies: [SolidWorks, Machining]
image: "/assets/images/lifting-device-design.png"
---
**By Joseph Gavacs**

[View PDF]({{ "/assets/images/Engine-Analysis.pdf" | relative_url }})

---

**Overview:**
	An internal combustion engine converts the chemical energy of fuel into mechanical work by mixing fuel and air, burning the mixture inside the engine cylinder and then using the high-pressure combustion gases to push the piston that converts its linear motion into rotational motion via a crankshaft.

---

**Key features:**

Ignition for specifically spark ignition (SI) internal combustion engines comes from the spark plug

Combustion occurs inside the working fluid (unlike steam or gas turbines with external combustion)

Operates cyclically

It can be treated as a closed system during compression/expansion (but not for intake/exhaust)

---

**Components:**

Cylinder - chamber where combustion occurs

Piston - converts gas pressure to mechanical motion

Crankshaft - converts reciprocating motion to rotation

Intake port - admits air/fuel mixture

Exhaust port - releases combustion products

Spark plug - initiates combustion

---

**The 4-Stroke Cycle:**

Intake:

The intake valve opens and the piston moves downward as air-fuel mixture enters the cylinder


Compression:

While both valves are closed, the piston moves upward and the mixture is compressed (pressure and temperature increase)


Power (Combustion):

Spark ignites mixture and rapid combustion increases pressure. This forces the piston downward and creates work output


Exhaust:

The exhaust valve opens and the piston moves upward. Combustion products are expelled (mostly carbon dioxide and water vapor)

---

**Balances:**

Mass Balance:

mair + mfuel = mexhaust

Δm = 0


Energy Balance:

dEcv/dt = Q - W + min hin - mout hout

0 = Qin - Qout + Wshaft + min hin - mout hout


Entropy Balance:

dScv/dt = Q/T - W + min sin - mout sout + Sgen

0 = Q/T - W + min sin - mout sout + Sgen

---

**Efficiency:**

Thermal Efficiency:

ηth = Wout/Qin

This will always be less than one due to heat loss from radiation, and work loss from friction


Otto Cycle Efficiency (Idealized Model):

ηotto = 1 - 1 / r^(𝛾 - 1)

r = Vmax/Vmin (compression ratio)

𝛾 = cp/cv

This models the efficiency of the engine if it were both adiabatic and isentropic, neither of which are true for a real engine but we can use this equation to see how we may be able to increase the efficiency

---

**Changes to Increase Efficiency:**

Increase Compression Ration (r):

From the efficiency equation for the Otto Cycle we can see that ηotto increases as r increases, thus increasing the ratio Vmax/Vmin will result in greater efficiency

Insulate Engine:

Insulating the engine would lower the Qout which allows more of the heat input to be converted to work rather than being lost through radiation out of the system
Brings the system closer to its adiabatic efficiency

---

**Conclusion:**
	The internal combustion engine operates in four main strokes: intake, compression, power, and exhaust. Although this cycle can be modelled by the idealized Otto Cycle, this idealization neglects the real world irreversibilities of friction and heat transfer across finite temperature differences. Nonetheless, the same factors that would increase the efficiency of the Otto Cycle also improve that of a real IC engine making it a useful comparison.

---
