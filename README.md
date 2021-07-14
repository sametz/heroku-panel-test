# heroku-panel-test

A test of deploying an NMR app to Heroku.

Besides working out the required setup for a Heroku Panel app,
the goal was to see how responsive an 8-spin second-order NMR simulation would be just using a free-tier Heroku server.
The simulation parameters are taken from the 8-spin default of WINDNMR.
The v0 slider changes the chemical shift of the lowest-frequency signal,
forcing a complete recalculation.
