# Modelica_StateGraph2

Free library providing components to model discrete event, reactive and hybrid systems in a convenient way with deterministic hierarchical state diagrams.

*Warning: Modelica_StateGraph2 is not fully Modelica compliant and will never be, since a better solution is now available with Modelica 3.3*

## Library description

The `Modelica_StateGraph2` library is a free Modelica package providing components to model discrete event, reactive and hybrid systems in a convenient way with deterministic hierarchical state diagrams. For convenience, the abbreviation "StateGraph2" will be often used for this library. An example model constructed with this library is shown in the figure to the right.

This library is inspired by Grafcet/Sequential Function Charts (SFC), Statecharts, Safe State Machines (SSM) and Mode Automata, and utilizes Modelica as action language. It has a similar modeling power as these formalisms, e.g. synchronization of parallel executing branches as in SFC (not easy in Statecharts), or suspending a hierarchical subgraph with one transition and resuming at the same states afterwards when entering it again, as in Statechart (not possible in SFC). A StateGraph2 model is always deterministic due to Modelicas "single assignment rule". Via special blocks in subpackage "Blocks", actions can be defined in a graphical way depending on the active step.

## Current release

Download [Modelica_StateGraph2 v2.0.2 (2013-10-01)](../../archive/v2.0.2.zip)

#### Release notes
*  Version v2.0.4
  * Uses Modelica Standard Library 3.2.3
  *  Version v2.0.3
  * Uses Modelica Standard Library 3.2.2
*  [Version v2.0.2 (2013-10-01)](../../archive/v2.0.2.zip)
  * Uses Modelica Standard Library 3.2.1
*  [Version v2.0.1 (2010-11-08)](../../archive/v2.0.1.zip)
  * Uses Modelica Standard Library 3.2
*  [Version v2.0 (2009-08-10)](../../archive/v2.0.1.zip)
  * First version of the `Modelica_StateGraph2` library based on `Modelica.StateGraph` and the prototype `ModeGraph` library from Martin Malmheden.

## License

This Modelica package is free software and the use is completely at your own risk;
it can be redistributed and/or modified under the terms of the [Modelica License 2](https://modelica.org/licenses/ModelicaLicense2).

## Development and contribution
Release manager: [Martin Otter](http://www.robotic.dlr.de/Martin.Otter)

You may report any issues with using the [Modelica Issue Tracker](https://trac.modelica.org/Modelica/newticket?component=_Modelica_StateGraph2).

## Acknowledgement
Partial financial support by BMBF (BMBF Förderkennzeichen: 01IS07022) for this work with-in the ITEA2 project [EUROSYSLIB](https://modelica.org/publications/newsletters/2009-1/index_html#eurosyslib) is highly appreciated.
