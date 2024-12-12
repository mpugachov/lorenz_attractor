# Lorenz Attractor

<bdl-fmi id="idfmi" mode="continuous" src="LorenzAttractor.js" fminame="LorenzAttractor" tolerance="0.000001" starttime="0" fstepsize="0.01" fpslimit="60" guid="{d9e9dc7d-3eea-4b1b-9096-418b67c67e14}" valuereferences="33554432,33554433" valuelabels="x,y" inputs="id1,16777216,1,1,t" inputlabels="sigma"></bdl-fmi>

<bdl-range id="id1" title="sigma" min="1" max="20" default="10" step="1"></bdl-range>


<bdl-chartjs-xy id="id10" width="400" height="400" fromid="idfmi" labels="x, y" initialdata="1, 0" refindex="0" refvalues="2"></bdl-chartjs-xy>
