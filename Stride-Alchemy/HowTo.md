# Notes on how to do the mechanics

* Electric conductivity : if two objects with conductive material types are in physical contact, both emit eletricity through particles and a boolean `IsConducting` turns true.

* Thermal conductivity : if two objects are in physical contact, the warmest's temperature is lowered by his thermal conductivity factor by seconds elapsed while the coolest raise his by the hottest's thermal conductivity factor. Air is considered as an object with a temperature that will never rise or lower.

* Magnetic field/ Wind field : Depending the material type and the presence of a force field, a material will receive a ``ForceImpulse*ElapsedTime``, the direction will be dictated by the vector field.