# MOC-NumPy
Design of a Minimum-Length De Laval Nozzle Using the Method of Characteristics

Generates the wall coordinates for a perfectly expanded, minimum-length 
supersonic nozzle using the Method of Characteristics. The solver maps a 
2D planar characteristic network to an axisymmetric area ratio, rigorously
pins the boundary conditions, and resamples the geometry using a shape-preserving 
spline to ensure equally spaced points for clean CAD/manufacturing import.
