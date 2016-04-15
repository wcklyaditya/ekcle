# ekcle
Chrome app to Display Power/Speed/Cadence from static bike trainer.
ANT+ or BLE(not available at the moment)

Power Curves taken from http://www.powercurvesensor.com/cycling-trainer-power-curves/
Image processed using http://arohatgi.info/WebPlotDigitizer/app/?
Plot fit data processed from https://plot.ly/ 3rd or higher order polynomial is used.

Elite Chrono Fluid Trainer curve fit
f(x) = a + b*x + c*x^2 + d*x^3
f(x) is the Power in Watts
x is the speed of the bike on the trainer.

a=1.6591168768491178
b=2.374718784595836
c=0.0014129663233588522
d=0.0030967878324862446
