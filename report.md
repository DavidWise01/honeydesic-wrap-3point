# Triple Decoisohedron Stack Report

- stack_normal_100: avg stability 0.94224, min stability 0.87536, EID calls 0, shell avg 0.84494
- stack_stress_ramp_100: avg stability 0.941, min stability 0.87517, EID calls 0, shell avg 0.8394
- stack_repeat_pressure_100: avg stability 0.94324, min stability 0.87695, EID calls 0, shell avg 0.85039


## Gravity Well ×27 Update

Desired stability band: 0.82–0.93.

Reason:
- below 0.82: too noisy / too loose
- above 0.93: too rigid / less adaptive
- 0.82–0.93: coherent but still able to move

The center is now specified as a 27-pulse gravity well. It pulls noisy branches inward while allowing coherent shell motion.
