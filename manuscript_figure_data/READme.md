# AIM: User-friendly GUI Program for Isotherm Fitting, Mixture Prediction, Isosteric Heat of Adsorption Estimation, and Breakthrough Simulation

This folder contains all the figures, the corresponding data, and MATLAB code used for plotting the figures in the manuscript.

## Files Directory:

```
.
├── Figure 1
│   └── Fig 1.png
├── Figure 2
│   └── Fig 2.png
├── Figure 3
│   └── Fig 3.png
├── Figure 4
│   └── Fig 4.png
├── Figure 5
│   └── Fig 5.png
├── Figure 6
│   └── Fig 6.png
├── Figure 7
│   └── Fig 7.png
├── Figure 8
│   └── Fig 8.png
├── Figure 9
│   ├── Data and Code
│   │   ├── CALF-20-CO2-b_1.svg
│   │   ├── CALF-20-CO2-b_2.svg
│   │   ├── CALF-20-CO2-q_{sat,1}.svg
│   │   ├── CALF-20-CO2-q_{sat,2}.svg
│   │   ├── CALF_20_marg_pos.csv
│   │   ├── CALF_20_marg_pos_bin_edge.csv
│   │   ├── CALF_20_params_bounds.csv
│   │   ├── CO2.bliso
│   │   ├── data
│   │   │   └── CALF_20_CO2_298K.csv
│   │   ├── isotherm_fit_opt.m
│   │   ├── plot_figure.m
│   │   └── plot_posteriors.m
│   └── Fig 9.png
├── Figure 10
│   ├── Data and Code
│   │   ├── Fig 10 (a)
│   │   │   ├── Isotherm.m
│   │   │   ├── Kr.bliso
│   │   │   ├── Xenon.bliso
│   │   │   ├── data
│   │   │   │   ├── SBMOF_1_krypton_298K.csv
│   │   │   │   └── SBMOF_1_xenon_298K.csv
│   │   │   └── plot_figure.m
│   │   └── Fig 10 (b)
│   │       ├── CH4.bliso
│   │       ├── CO2.bliso
│   │       ├── Isotherm.m
│   │       ├── data
│   │       │   ├── CALF_20_CO2_298K.csv
│   │       │   └── CALF_20_methane_298K.csv
│   │       └── plot_figure.m
│   └── Fig 10.png
├── Figure 11
│   ├── Data and Code
│   │   ├── Fig 11 (a)
│   │   │   ├── data
│   │   │   │   ├── He_IAST.csv
│   │   │   │   ├── He_Lang.csv
│   │   │   │   ├── Helium_RUPTURA.data
│   │   │   │   ├── Kr_IAST.csv
│   │   │   │   ├── Kr_Lang.csv
│   │   │   │   ├── Kr_RUPTURA.data
│   │   │   │   ├── Xe_IAST.csv
│   │   │   │   ├── Xe_Lang.csv
│   │   │   │   └── Xe_RUPTURA.data
│   │   │   └── plot_figure_code.m
│   │   └── Fig 11 (b)
│   │       ├── data
│   │       │   ├── CH4_IAST.csv
│   │       │   ├── CH4_Lang.csv
│   │       │   ├── CH4_RUPTURA.data
│   │       │   ├── CO2_IAST.csv
│   │       │   ├── CO2_Lang.csv
│   │       │   ├── CO2_RUPTURA.data
│   │       │   ├── Helium_IAST.csv
│   │       │   ├── Helium_Lang.csv
│   │       │   └── Helium_RUPTURA.data
│   │       └── plot_figure_code.m
│   └── Fig 11.png
├── Figure 12
│   ├── Data and Code
│   │   ├── Fig 12 (a)
│   │   │   ├── data
│   │   │   │   ├── He_IAST.csv
│   │   │   │   ├── He_Lang.csv
│   │   │   │   ├── Helium_RUPTURA.data
│   │   │   │   ├── Kr_IAST.csv
│   │   │   │   ├── Kr_Lang.csv
│   │   │   │   ├── Kr_RUPTURA.data
│   │   │   │   ├── Xe_IAST.csv
│   │   │   │   ├── Xe_Lang.csv
│   │   │   │   └── Xe_RUPTURA.data
│   │   │   └── plot_figure_code.m
│   │   └── Fig 12 (b)
│   │       ├── data
│   │       │   ├── CH4_IAST.csv
│   │       │   ├── CH4_Lang.csv
│   │       │   ├── CH4_RUPTURA.data
│   │       │   ├── CO2_IAST.csv
│   │       │   ├── CO2_Lang.csv
│   │       │   ├── CO2_RUPTURA.data
│   │       │   ├── Helium_IAST.csv
│   │       │   ├── Helium_Lang.csv
│   │       │   └── Helium_RUPTURA.data
│   │       └── plot_figure_code.m
│   └── Fig 12.png
├── Figure 13
│   ├── Data and Code
│   │   ├── Case_study_2.m
│   │   ├── Data
│   │   │   ├── Isotherm_273.csv
│   │   │   ├── Isotherm_298.csv
│   │   │   ├── Isotherm_323.csv
│   │   │   ├── heat_273.csv
│   │   │   ├── heat_298.csv
│   │   │   └── heat_323.csv
│   │   ├── Q_ads_CO2.svg
│   │   ├── Q_ads_full_range.svg
│   │   ├── isotherm_CO2_ln.svg
│   │   └── isotherm_fit_opt.m
│   └── Fig 13.png
├── Figure 14
│   ├── Data and Code
│   │   ├── CALF-20-CO2-case
│   │   │   ├── Q_ads.svg
│   │   │   ├── a_{0}.svg
│   │   │   ├── a_{1}.svg
│   │   │   ├── a_{2}.svg
│   │   │   ├── a_{3}.svg
│   │   │   ├── a_{4}.svg
│   │   │   ├── a_{5}.svg
│   │   │   ├── b_{0}.svg
│   │   │   ├── b_{1}.svg
│   │   │   └── b_{2}.svg
│   │   ├── CALF-20_margpos.csv
│   │   ├── CALF-20_margpos_bin_edges.csv
│   │   ├── CALF-20_params_bound.csv
│   │   ├── GCMC_CALF_20_UA.m
│   │   └── plot_posteriors.m
│   └── Fig 14.png
├── Figure 15
│   ├── Data and Code
│   │   ├── data
│   │   │   ├── CO2_data.csv
│   │   │   ├── Helium.csv
│   │   │   ├── N2_data.csv
│   │   │   └── Temperature.csv
│   │   ├── plot_composition.m
│   │   └── plot_temperature.m
│   └── Fig 15.png
├── READme.md
```