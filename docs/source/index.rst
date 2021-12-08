Welcome to MoSwA Documentation!
===================================

**Motif SWitch Analyser** is a tool that not only identifies all alignment k-mer positions that exhibit 
motif switching, but also provides a multi-faceted and extensive characterisation of the switches. This includes:

*	a short statistical summary on the switches observed;
*	an alignment view of all the switches observed in a given dataset, referenced against a consensus sequence built from the index sequences of the k-mer positions;
*	a network graph showing the dynamic interaction between the motif switches;
*	a bar plot showing clusters of motif switch positions, as well as hotspots in the protein alignment;
*	index switch positions are noteworthy and highlighted because highly conserved index at such positions are possibly to be avoided as vaccine targets given the instability of the index;
*	a pairwise alignment score based on PAM30 is provided for index switches, to determine the physico-chemical spectrum of similarity/variability between the index sequence and the replacing variant motif sequence. 

You can simply upload your aligned file to `MoSwA Web <http://moswa.bioinfo.perdanauniversity.edu.my//>`_
which offers a *simple* and *intuitive* usage.

Check out the :doc:`usage` section for further information, including
how to :ref:`install` version of MoSwA.


Contents
--------

.. toctree::
   :maxdepth: 2
   :glob:
   :numbered:
   usage
   results
   algo
