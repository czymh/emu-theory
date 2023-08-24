## CSST Emulator with Theory 
This is a surrogate model for the CSST (China Space Station Telescope; 中国巡天空间望远镜) emulator.
Here, we use theoretical predictions of different cosmological statistics, e.g., power spectrum, two-point correlation function, and halo mass function to construct the emulator.
The cosmological sampling and interpolation are the same as the final model in principle. 
Finally, we replace these theoretical models with our simulation results (under process).


![Density contrast fields of different cosmologies with length 200 Mpc/h.](https://github.com/czymh/emu-theory/blob/master/pic/field_cosmos_lowres.gif?raw=true)


![Density contrast fields of different cosmologies with length 24 Mpc/h.](https://github.com/czymh/emu-theory/blob/master/pic/halo_cosmos_lowres.gif?raw=true)


All data has been calculated so the only extra Python package is [sklearn](https://scikit-learn.org/stable/).
