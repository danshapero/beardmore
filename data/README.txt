This directory contains a set of alternate realizations of the Beardmore bed, based on a combination of bedmap data and data from airborne radar sounding, along with elevations of exposed rock.  We used the Beardmore data mask to identify cells that were directly constrained by previous radar surveys, and combined the elevations from these cells with data from our own radar data sets, and with exposed-rock elevations from the REMA project digital elelvation model.  We then applied two different gridding strategies: an isotropic smooth surface fit, which finds a minimum-curvature surface that approximately matches the data points, and an anisotropic surface fit, that strongly minimizes curvature in the direction parallel to ice flow, and weakly minimizes curvature in the direction perpendicular to ice flow. These data are stored in geotif-format files in this directory, along with maps showing the location of data used to constrain the maps:


The files in this directory are:

bedmachine_anisotropic_interp.tif		: 1-kmx1-km grid of bed elevations generated with the anisotropic interpolator
bedmachine_anisotropic_interp_constraints.tif	: locations for the anisotropic data constraints
bedmachine_isotropic_interp.tif			: 1-kmx1-km grid of bed elevations generated with the isotropic interpolator
bedmachine_isotropic_interp_constraints.tif	: locations for the isotropic data constraints
bedmachine_interp.tif				: Bedmachine elevations interpolated to the same grid as the reinterpolated data

All data are presented on a 1-km polar-stereographic grid (EPSG:3031) with elevations relative to the WGS84 ellipsoid

