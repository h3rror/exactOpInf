# exactOpInf

This is the Matlab implementation of the numerical experiments reported in: 

https://arxiv.org/abs/2506.01244

Call the scripts <tt>chafee_infante.m</tt>, <tt>ice_sheet.m</tt> and to <tt>burgers.m</tt> to perform the numerical experiments.

<tt>chafee_infante.m</tt> and <tt>burgers.m</tt> take only a few seconds.

<tt>ice_sheet.m</tt> takes approx. 5 minutes if the boolean <tt>generatePODdata</tt> is set to  <tt>true</tt>, so the POD snapshot data is generated from scratch.

Otherwise, if the boolean <tt>generatePODdata</tt> is set to  <tt>false</tt>, the POD snapshot data is loaded and <tt>ice_sheet.m</tt> takes approx. 3 minutes.

Call <tt>plot_operator_errors.m</tt> to generate the operator error and condition number plots.
