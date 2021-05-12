NOTE: This repo is defunct and has been archived.
======================================================


Distributed Monte Carlo Simulation Framework
============================================

The Distributed-MCS Framework is a Python package designed to run Monte Carlo simulations on a multiprocessor computing system. The primary functionality is implemented in Core-MCS, which is designed to execute a user’s model as a “black box”: the specific purpose of the model is irrelevant to Core-MCS. The only requirements of the model are that it can be executed on the multiprocessor system and that it can read input data from a local file. To use the analysis tools provided, some results of the simulation must be saved to the Core-MCS database.

Core-MCS consists of a set of Python modules, a command-line Python script (mcs), a relational database, parameter input files, parameter distribution files, and system configuration files, all of which are described in the User Guide. The Core-MCS system is designed to be customized; indeed, the Core-MCS requires some degree of customization to be used with any model. The initial release provides three customized systems that support the GTAP computable global equilibrium model (GTAP-MCS), a customization of GTAP-MCS called ILUC-MCS, and the GCAM integrated assessment model (GCAM-MCS).

There will soon be a User's Guide to using the framework, and a Developer's Guide to extending the framework to support an additional model input/output formats.
