# New TEP datasets

New datasets for the Tenessee Eastman Process benchmark (Downs and Vogel, 1993). 

Continuous simulations were carried out. Fults were randomly chosen as well as their durations, and between two periods of fault there is always one period of normal operation (with its duration also randomly chosen). 


Available datasets:
- *python_data_1year.csv:* Data corresponding to 1 year of operation. Simulations used the FORTRAN codes proposed by the Braazt's group (Russell et al., 2000; Chiang et al., 2000) and wrapped in Python by Câmara (2019). File shape: (175200, 54).
- *python_data_3years.csv:* Data corresponding to 3 years of operation. Simulations used the FORTRAN codes proposed by the Braazt's group (Russell et al., 2000; Chiang et al., 2000) and wrapped in Python by Câmara (2019). File shape: (525600, 54).
- *matlab_data_1year.csv:* Data corresponding to 3 years of operation. Simulations used a revised model proposed by Professor Lawrence Ricker from Washington University (Ricker, 2005; Bathelt et al. 2014) and implemented in MATLAB/Simulink. File shape: (175200, 54).

# References

Bathelt, A., Ricker, N. L., Jelali, M., 2014. Revision of the Tennessee Eastman Process model. IFAC-PapersOnLine, v. 48, p. 309-314. https://doi.org/10.1016/j.ifacol.2015.08.199.

Câmara, M. M., 2019. GitHub. tep2py. https://github.com/camaramm/tep2py.

Chiang, L. H., Russell, E. L., Braatz, R. D., 2000. Fault diagnosis in chemical processes using Fisher discriminant analysis, discriminant partial least squares, and principal component analysis. Chemometrics and Intelligent Laboratory Systems, v. 50, p. 243-252. https://doi.org/10.1016/S0169-7439(99)00061-1.

Downs, J. J., Vogel, E. F., 1993. A plant-wide industrial process control problem. Computers & Chemical Engineering, v. 17, n. 3, p. 245-255. https://doi.org/10.1016/0098-1354(93)80018-I.

Russell, E. L., Chiang, L. H., Braatz, R. D., 2000. Fault detection in industrial processes using canonical variate analysis and dynamic principal component analysis. Chemometrics and Intelligent Laboratory Systems, v. 51, p. 81-93. https://doi.org/10.1016/S0169-7439(00)00058-7.
