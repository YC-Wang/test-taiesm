### TaiESM2 ZM Trigger Function Extension

This GitHub repository provides an implementation of a trigger function integrated into the Zhang-McFarlane (ZM) convection scheme for use in TaiESM2.

The trigger function enables convection activation within the ZM scheme, such as CIN and lifting original levels.
The code is originally implemented in the CAM5.3 and now migrates to CAM7.
Similar design is also used in E3SM developed by DOE.

* Citations: Wang et al. (2015), Lee et al. (2021), Wang et al. (2021)
* Wang, Y.-C., H.-L. Pan, and H.-H. Hsu (2015), Impacts of the triggering function of cumulus parameterization on warm-season diurnal rainfall cycles at the Atmospheric Radiation Measurement Southern Great Plains site, J. Geophys. Res. Atmos., 120, 10,681–10,702, doi:10.1002/2015JD023337.
https://agupubs.onlinelibrary.wiley.com/doi/full/10.1002/2015JD023337


🔗 Original TaiESM2 Repository

For the full TaiESM2 model and documentation, please refer to the official repository:
👉 https://github.com/rceclccr/TaiESM2

The two files are:
> $CESM3/components/cam/src/atmos_phys/zhang_mcfarlane/zm_convr.F90
> 
> $CESM3/components/cam/src/physics/cam/zm_conv_intr.F90
