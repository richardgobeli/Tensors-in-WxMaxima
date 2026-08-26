# Tensors-in-WxMaxima
There is a collection of many different GR and Tensor exploring worksheets here. Work is in progress on adding more worksheets.

The mac files can be use as demo files in maxima.bat or xmaxima.bat.

The wxm files are used in WxMaxima.

- ivary.mac or ivary.wxm is a work sheet showing how to generate tensor variation and Euler-Lagrange Equation.
- Hagihara Coframe.mac shows how to find the frame for a equatorial circular orbit around a body of mass m.
It also has generated the Stress-Energy Tensor for the Hagihara orditing object.
The wxm form of the file has questions in the file that causes command line maxima to abort.
- The Lagraingian Density of The Electromagnetic Field.mac is from Viktor T. Toth.
- Modified itensor.lisp to have the ishow give a better index display without stacking indices from top to bottom.
It aslo fixes a small bug where if a -index is found as a contravariant index because of a tensor derivative it will
indicate it as a covariant index.
