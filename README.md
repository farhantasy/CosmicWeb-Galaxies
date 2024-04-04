FARHANUL HASAN (farhasan@nmsu.edu)

The galaxy catalogs are named "TNG100_gal_mcpm_[snap].txt", where [snap] is snapshot number.

The columns of each file are as follows (some of these are from https://www.tng-project.org/data/docs/specifications/):

parentID = SubhaloParent from the TNG data access site

galID = SubfindID (subhalo/galaxy ID) from the TNG data access site

haloID = GroupID (halo ID) from the TNG data access site

gal_x, gal_y, gal_z = SubhaloCM from the TNG data access site, in comoving Mpc 

rh = Group_R_Crit200from (halo virial radius R_200,c) from the TNG data access site, in comoving Mpc 

mh = Group_M_Crit200from (halo virial mass M_200,c) from the TNG data access site, in solar mass

ms = SubhaloMassType for stars (total stellar mass M*) from the TNG data access site, in solar mass
ms_2re = SubhaloMassInRadType for stars (stellar mass within twice stellar half-mass radius) from the TNG data access site, in solar mass
mg = SubhaloMassType for gas (total gas mass Mgas) from the TNG data access site, in solar mass
mg_2re = SubhaloMassInRadType for gas (gas mass within twice stellar half-mass radius) from the TNG data access site, in solar mass
mg_h = MassType for gas (total gas mass of the halo) from the TNG data access site, in solar mass
mbh = SubhaloMassType for black holes (total BH mass Mbh) from the TNG data access site, in solar mass
sfr = SubhaloSFR (total SFR of all gas cells) from the TNG data access site, in solar mass/yr
sfr_2re =  = SubhaloSFRinRad (SFR within twice stellar half-mass radius) from the TNG data access site, in solar mass/yr
spin_x, spin_y, spin_z = SubhaloSpin (total spin of all particles) from the TNG data access site, in units of Mpc*(km/s)
bhmdot = SubhaloBHMdot (Sum of the instantaneous BH accretion rates of all BH) from the TNG data access site, in units of solar mass/yr
mag_U, mag_B, mag_V, mag_g, mag_r, mag_i, mag_z = SubhaloStellarPhotometrics in the U,B,V (Buser, 1978) and g,r,i,z (SDSS) bands from the TNG data access site, in units of absolute magnitude
d_node_mcpm = comoving distance of a galaxy to the nearest cosmic web node, as identified by DisPerSE from the MCPM density field, in comoving Mpc
d_fil_mcpm = transverse comoving distance of a galaxy to the nearest cosmic web filament spine, as identified by DisPerSE from the MCPM density field, in comoving Mpc
d_halo_normrh = comoving distance of a galaxy to the nearest massive (0.5% most massive at the snapshot) halo, normalized by the virial radius (rh) of the halo
angle_mcpm = angle between the direction of galaxy spin and that of local filament segment, in degrees (between 0 and 90 degrees), for filaments identified by DisPerSE from the MCPM density field
fildens_mcpm = filament line density, MCPM overdensity summed over the nearest filament segment per unit length of the segment, for filaments identified by DisPerSE from the MCPM density field, in units of 1/comoving kpc
d_node_dtfe = comoving distance of a galaxy to the nearest cosmic web node, as identified by DisPerSE from the DTFE density field, in comoving kpc
d_fil_dtfe = transverse comoving distance of a galaxy to the nearest cosmic web filament spine, as identified by DisPerSE from the DTFE density field, in comoving kpc
angle_dtfe = = angle between the direction of galaxy spin and that of local filament segment, in degrees (between 0 and 90 degrees), for filaments identified by DisPerSE from the DTFE density field
overdensity_dtfe = DTFE overdensity at the location of the galaxy
fildens_dtfe = filament line density, MCPM overdensity summed over the nearest filament segment per unit length of the segment, for filaments identified by DisPerSE from the DTFE density field, in units of 1/comoving kpc
seglength_mcpm = length of nearest filament segment, for filaments identified by DisPerSE from the MCPM density field, in comoving kpc
seglength_dtfe = length of nearest filament segment, for filaments identified by DisPerSE from the DTFE density field, in comoving kpc
persistence_mcpm = average persistence of the two critical points at the ends of the nearest identified filament, for filaments identified by DisPerSE from the MCPM density field
persistence_dtfe = average persistence of the two critical points at the ends of the nearest identified filament, for filaments identified by DisPerSE from the DTFE density field
galdens_mcpm = MCPM overdensity at the location of the galaxy
ngal_1, ngal_2, ngal_5 = Number of galaxies + 1 within spheres of radii 1, 2, and 5 comoving Mpc, respectively
