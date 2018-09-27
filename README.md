# Tracer
This project is a path tracer. It is developed in Qt. Multi-importance sampling and Ruassian roulette termination are used to make the integrator converge faster. Micro-facet model and fresnell effect are implemented. Constructive solid geometry and signed distance field are used to produce procudural complex geometry. A experimental photon mapper is also included.

* ### Lens Based Camera 
###### Fulllight Integrator 1024x1024 pixels 20x20 samples 5 maximum recursions 1.5 hours

![](1_1024_20_5_1.5h.png)
=====

* ### Lens Based Camera 
* ### BVH + KD Tree
* ### Texture
* ### Normal Map
###### Fulllight Integrator 1024x1024 pixels 20x20 samples 5 maximum recursions 6 hours

![](2_1024_20_5_6h.png)
=====

* ### BVH + KD Tree
* ### Chrome Material
###### Fulllight Integrator 1024x1024 pixels 20x20 samples 5 maximum recursions 63.5 hours

![](3_1024_20_5_63.5h.png)
=====

* ### BVH + KD Tree
* ### Texture 
* ### Normal Map
* ### Chrome Material
###### Fulllight Integrator 1024x1024 pixels 20x20 samples 5 maximum recursions 7.8 hours

![](4_1024_20_5_7.8h.png)
=====

* ### Implicit Surface
* ### Chrome Material
###### Fulllight Integrator 400x400 pixels 10x10 samples 5 maximum recursions 5.6 hours

![](5_400_10_5_5.6h.png)
=====

* ### Implicit Surface
* ### Chrome Material
###### Fulllight Integrator 400x400 pixels 20x20 samples 5 maximum recursions 60 hours

![](5_400_20_5_60h.png)
=====

* ### Contructive Solid Geometry
* ### Difference and Union
###### Fulllight Integrator 400x400 pixels 20x20 samples 5 maximum recursions 1 minute

![](CSG_difference_union.png)
=====

* ### Constructive Solid Geometry
* ### Intersection and Union
###### Fulllight Integrator 400x400 pixels 20x20 samples 5 maximum recursions 1 minute

![](CSG_intersection_union.png)
=====

* ### Directional Light
###### Fulllight Integrator 400x400 pixels 20x20 samples 5 maximum recursions 10 minutes

![](DirectionalLight.png)
=====

* ### Environment Light
###### Fulllight Integrator 400x400 pixels 20x20 samples 5 maximum recursions 1 minute

![](EnvironmentLight.png)
=====

* ### Experimental Photon Mapper
###### Photon Integrator 500,000 photons emitted, sampling radius 1.9

![](photon_500000_1.9.png)

###### Photon Integrator 2,000,000 photons emitted, sampling radius 1.8

![](photon_2000000_1.8.png)
=====