# settlingBed_polyDisperse
A 2D liquid-solid (particulate) phase model settling under gravity. Particles break-apart as time passes.

Particles break apart at constant rate (represented using powerLaw to the power of zero) independent of particle size.

BUG:
Current iteration, as of 16.06.2021, the particle breakage does not conserve number. 
Prior iteration without inclusion of breakage had converged successfuly indicating current issue should only be from breakage configuration  
