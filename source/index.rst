.. helloworld documentation master file, created by
   sphinx-quickstart on Sun Mar 31 19:09:02 2024.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Spider's documentation!
===================================

Spider – a flexible and unified framework for simulating ST data.
===============================================================================================


.. toctree::
   :maxdepth: 1
   :caption: Contents:

   Installation
   Tutorial1_reference_based_tutorial

.. image:: ../figures/workflow.png
   :width: 1400

Overview
========
Spider is a flexible and unified framework for simulating ST data by leveraging spatial neighborhood patterns among cells through a conditional optimization algorithm. 
By inputting spatial patterns extracted from real data or user-specified transition matrix, 
Spider assigns cell type labels through the BSA algorithm that improves the computational efficiency of conventional simulated annealing algorithm. 
Gene expression profiles for individual cell types can be generated either using real or simulated data by Splatter or scDesign2. 
Finally, spot-level ST data can be simulated by aggregating cells inside generated spots using 10X spatial encoding scheme or user-specified generation rules.
