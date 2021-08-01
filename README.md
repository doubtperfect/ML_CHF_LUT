# ML_CHF_LUT
1. The ML LUT uses Groeneveld 2006 CHF LUT as based and predicts the correction errors for each point;
2. The input parameters used for ML LUT are: pressure p (kPa), mass flux G (kg/m^2s), hydraulic diameter D (m) and local quality X_e (-);
3. The ragnes for each paramters: \
  p = [100,300,500,1000,2000,3000,5000,7000,10000,12000,14000,16000,18000,20000,21000] \
  G = [0,50,100,300,500,750,1000,1500,2000,2500,3000,3500,4000,4500,5000,5500,6000,6500,7000,7500,8000] \
  D = [0.002, 0.005, 0.008, 0.011, 0.014, 0.017, 0.02, 0.023, 0.026, 0.029, 0.032, 0.035, 0.038, 0.041] \
  X = [-0.5,-0.4,-0.3,-0.2,-0.15,-0.1,-0.05,0,0.05,0.1,0.15,0.2,0.25,0.3,0.35,0.4,0.45,0.5,0.6,0.7,0.8,0.9,1] \
4. When predicting the base using Croeneveld CHF LUT, hydraulic diamter should be used for tube and heated diameter should be used for annulus;
5. Tube and annulus LUT files are grouped according to the hydraulic diameter. Within each file, the matrices are grouped according to pressure.
