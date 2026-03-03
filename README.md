To those interested in probing the inherent diffusion properties of their electrode materials, intermittent current interruption (ICI) and 
galvanostatic intermittent titration technique (GITT) are both great options. Operating on the same working physics, these techniques measure 
the time-dependent resistance to ion diffusion - a necessary transport phenomenon that can bottleneck the charge compensation reaction. With 
carefully timed constant current charge pulses and rests, the concentration overpotential can be isolated from the ohmic and kinetic overpotentials. 
This allows a mathematical calculation of the diffusion coefficient following Fick's laws, given that certain physical criteria are met. The ICI 
technique was developed by Matthew J. Lacey and can be read about thoroughly in his papers. In my experiments, ICI-calculated diffusion data has 
proven to lie almost directly ontop of diffusion data calculated by the industry standard GITT method.

These scripts have few inputs such as test result file names, mean active material particle radius, and protocol charge / rest step numbers. The 
output is an easy to read plot of diffusion coefficient as a function of cell voltage accompanied by a data summary in csv form. The calculations 
are fairly intensive resulting in run times from a few seconds for one or a few samples up to ~five-ten minutes for larger data sets (40 test files at once).
