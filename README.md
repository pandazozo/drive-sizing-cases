# Drive sizing cases (computed examples)

A small set of **computed** torque/speed/power cases for screening a drive:

- `torque-speed-power.csv` — rated power vs base speed, resulting torque, 4-pole 50 Hz synchronous speed, slip at base speed.

Formulas: `P[kW] = T[N·m] · n[rpm] / 9550`, `n_s = 120·f/p`, `s = (n_s − n)/n_s`.

These are arithmetic identities, not measurements. Real sizing needs duty cycle,
overload, thermal and inverter limits.

Reference material and worked boundaries:
- <https://www.powermindmesh.com/tools/>
- <https://www.powermindmesh.com/methods/>
- <https://www.powermindmesh.com/tools/torque-speed-power/>

MIT.
