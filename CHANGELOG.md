# Change Log

## Version 0.10.4
- make three js peer dependencies

## Version 0.10.3
- fix bugs caused by three.js version upgrade

## Version 0.10.0
- Support BSDF material MeshStandardMaterial and MeshBasicMaterial (Unlit)
- Move texture, blend, transparent, side, and other material related setting to material properties in particle system

## Version 0.9.0
- Decouple QuarksLoader from batchRenderer. Remove BatchRenderer in QuarksLoader constructor
- Fix many bugs involving scale of the particle system
- Refactor many code names involving particle to VFX.
- Add texture sequencer behavior
- Add grid emitter

## Version 0.8.0
- Add WIP node-based behavior
- Support sub-emission system
- Support mesh surface emitter

## Version 0.7.0
- Remove update(delta) function on individual particle systems. 
Users do not need to call this function anymore manually. Add delta
parameter to BatchedParticleRenderer, which updates all registered
particle systems.
- Add a new behavior EmitSubParticleSystem, which emit a new particle emitter 
from a particle in the current system. 
- Fix MeshSurfaceEmitter's index bug.
