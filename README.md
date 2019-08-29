# Trackpy

## Connecting animal tracking and mesoscale oceanographic data
***

#### Collaborators

+ Hannah Blondin (hblondin at stanford dot edu)
+ James Fahlbusch (musculus at stanford dot edu)
+ Will Oestreich (woestreich at stanford dot edu)

***

### Background

Understanding the underlying oceanographic drivers of the movements of pelagic marine organisms has been a major area of research interest for both primary and applied marine ecologists in recent years. Several recent studies leveraging animal tracking data and remotely-sensed oceanographic data have elucidated the importance of mesoscale oceanographic features, including eddies and filaments, to movements of highly-mobile pelagic organisms (e.g. Braun et al., 2019; Gaube et al., 2018; Abrahms et al., 2018). Open-source tools for linking such animal movements to oceanographic remote sensing data are of interest (see Dodge et al., 2013 for an R-based tool), yet simple tools for linking animal movements to databases of value-added mesoscale oceanographic features derived from remote sensing products are not readily available.

#### Resources

- https://www.aviso.altimetry.fr/fileadmin/documents/data/tools/hdbk_eddytrajectory_2.0exp.pdf

### Goals

Provide an illustrative example for Python beginners to link animal movement data with databases of mesoscale oceanographic features and visualize these interactions.

### Datasets

1. Simulated loggerhead turtle (Caretta caretta) satellite tag tracks.

2. AVISO+ Mesoscale Eddy Trajectory Atlas Product 
 
### Workflow
1. Upload animal track data

2. Access AVISO+ mesoscale eddy data product

3. Slice mesoscale eddy dataset for spatiotemporal domain of animal tracks

4. Visualize animal-feature interactions in space and time

5. Summarize interactions


### References
Abrahms, B., Scales, K.L., Hazen, E.L., Bograd, S.J., Schick, R.S., Robinson, P.W. and Costa, D.P., 2018. Mesoscale activity facilitates energy gain in a top predator. Proceedings of the Royal Society B: Biological Sciences, 285(1885), p.20181101.

Braun, C.D., Gaube, P., Sinclair-Taylor, T.H., Skomal, G.B. and Thorrold, S.R., 2019. Mesoscale eddies release pelagic sharks from thermal constraints to foraging in the ocean twilight zone. Proceedings of the National Academy of Sciences, p.201903067.

Chelton, D.B., Schlax, M.G. and Samelson, R.M., 2011. Global observations of nonlinear mesoscale eddies. Progress in Oceanography, 91(2), pp.167-216.

Dodge, S., Bohrer, G., Weinzierl, R., Davidson, S.C., Kays, R., Douglas, D., Cruz, S., Han, J., Brandes, D. and Wikelski, M., 2013. The environmental-data automated track annotation (Env-DATA) system: linking animal tracks with environmental data. Movement Ecology, 1(1), p.3.

Gaube, P., Braun, C.D., Lawson, G.L., McGillicuddy, D.J., Della Penna, A., Skomal, G.B., Fischer, C. and Thorrold, S.R., 2018. Mesoscale eddies influence the movements of mature female white sharks in the Gulf Stream and Sargasso Sea. Scientific reports, 8(1), p.7363.



### Required Packages
Folium:
conda install folium -c conda-forge

matplotlib

ftplib

getpass


