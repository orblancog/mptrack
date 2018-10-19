oblancog 2018/NOV/19

The main file is job.madx. The mt.madx lattice transports three beams : mu+ at 22.5GeV, mu- at 22.5GeV and e+ at 45GeV.
The length is 14.1m, the betastar=0.1m for the three beams and both planes, it is apochromatic for muons, and W=30 for positrons.
Quad gradients are below 100T/m, they are 0.75m long, and the distance between magnets is 0.2m.

The transport lattice is used as cell for a ring, in order to get a twiss file of a closed machine.

Trying to generate geometry with MDISim as :
*  Tfs2Geom -csv -- mtline IPMT -1 15 1 600 acc_twiss.tws


