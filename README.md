This file is https://github.com/WilliamIngramAtmosphericPhysics/IngramBushell2021/README
It describes the other files here, which contain all that is needed to reproduce the figures in Ingram & Bushell (2021, GRL).
Fig1points contains numbers that will give the points in Fig 1, as well as other information such as model names and explanation of its content and format.
Fig1connexions contains indices to link CMIP5 GCMs to "corresponding" CMIP6 GCMs, similarly with other information.
Fig1plot is python code to read these files and plot Fig 1.
globalmeannumbers contains the numbers plotted in Fig 2 and Fig S3, plain text with short verbal descriptions.
zonalmeannumbers contains the numbers plotted in Fig S2 and Fig S4, plain text with short verbal descriptions, and -1.07374e+09 to mark points not to be plotted when showing notional significance.
plot2levelssetsandthicknesses.py contains python code to plot Fig S1 - once imported and compiled, "plot2levelssetsandthicknesses.plot2levelssetsandthicknesses()" should reproduce the figure.
