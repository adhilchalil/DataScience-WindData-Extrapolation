# DataScience-WindData-Extrapolation

 This python scripts make use of 7 GBs worth of wind data on different building structures to calculate/extrapolate winddata and should be added into the local directory.
 If not expecting to rerun curve fitting, the mean value file is sufficient for testing out prediction based on "Mean pc Data T111_4_.txt" for specific building size.
 
 Run ipynb file once the data is set up or partially run it to quickly get the basic test run using "Mean pc Data T111_4_.txt".

 Also provides APIs using flask framework once the script is up and running.

 API Url/parameters expected: "http://localhost:5000/?x={x-point}&y={y-point}&side={sideAsInteger}&winddirection={windAngle}&model={modeltype}"

 values accepted for modeltype: "linear", "logistic","svr_linear","svr_rbf"
