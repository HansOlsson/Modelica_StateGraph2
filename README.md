# Modelica_StateGraph2

Free library providing components to model discrete event, reactive and hybrid systems in a convenient way with deterministic hierarchical state diagrams.

*Warning: Modelica_StateGraph2 is not fully Modelica compliant and might never be. Modelica 3.3 introduced state machines as a replacement for clocked systems. However, for non-clocked systems the situation is less clear. One possibility is that some of the good ideas from this library are integrated in Modelica.StateGraph in a Modelica compliant way.*

## Library description

The `Modelica_StateGraph2` library is a free Modelica package providing components to model discrete event, reactive and hybrid systems in a convenient way with deterministic hierarchical state diagrams. For convenience, the abbreviation "StateGraph2" will be often used for this library. An example model constructed with this library is shown in the figure to the right.

This library is inspired by Grafcet/Sequential Function Charts (SFC), Statecharts, Safe State Machines (SSM) and Mode Automata, and utilizes Modelica as action language. It has a similar modeling power as these formalisms, e.g. synchronization of parallel executing branches as in SFC (not easy in Statecharts), or suspending a hierarchical subgraph with one transition and resuming at the same states afterwards when entering it again, as in Statechart (not possible in SFC). A StateGraph2 model is always deterministic due to Modelicas "single assignment rule". Via special blocks in subpackage "Blocks", actions can be defined in a graphical way depending on the active step.

## Current release

Download [Modelica_StateGraph2 v2.1.0 (2020-06-04)](https://github.com/HansOlsson/Modelica_StateGraph2/releases/download/v2.1.0/Modelica_StateGraph2-release.zip)

#### Release notes
*  [Version v2.1.0 (2020-06-04)](https://github.com/HansOlsson/Modelica_StateGraph2/releases/download/v2.1.0/Modelica_StateGraph2-release.zip)
   * Uses Modelica Standard Library 4.0.0. And some minor fixes.
*  [Version v2.0.5 (2020-04-02)](https://github.com/HansOlsson/Modelica_StateGraph2/releases/download/v2.0.5/Modelica_StateGraph2-release.zip)
   * Some minor fixes. Be closer to standard Modelica and avoid problematic example.
*  [Version v2.0.4 (2019-03-20)](https://github.com/HansOlsson/Modelica_StateGraph2/releases/download/v2.0.4/Modelica_StateGraph2-release.zip)
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
Release manager: Hans Olsson, previously [Martin Otter](http://www.robotic.dlr.de/Martin.Otter)

You may report any issues with using [GitHub Issue tracker](https://github.com/HansOlsson/Modelica_StateGraph2/issues).

## Acknowledgement
Partial financial support by BMBF (BMBF Förderkennzeichen: 01IS07022) for this work with-in the ITEA2 project [EUROSYSLIB](https://modelica.org/publications/newsletters/2009-1/index_html#eurosyslib) is highly appreciated.
