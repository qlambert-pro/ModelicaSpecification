# Modelica Change Proposal MCP-0027<br/>Units of Literal Constants
Francesco Casella, Henrik Tidefelt

**(In Development)**

## Summary
The purpose of this MCP is to allow more unit errors to be detected by giving more expressions the unit `"1"` instead of having an undefined unit.
The problem with undefined unit is that it gets in the way of carrying out checking of units (which tools tend to deal with by not checking units at all where this happens).

## Revisions
| Date | Description |
| --- | --- |
| 2022-10-04 | Henrik Tidefelt. Filling this document with initial content. |

## Contributor License Agreement
All authors of this MCP or their organizations have signed the "Modelica Contributor License Agreement".

## Rationale
FIXME

## Backwards Compatibility
This MCP defines unit checking with deprecated semantics that allow not checking anything, and hence it does not immediately break backwards compatibility.
Of course, backwards compatibility should ultimately be broken by removing the deprecated semantics.
The structure of the proposal is such that this can be done gradually.

## Tool Implementation
Unit checking in System Modeler is made according to this proposal (with some extensions).

### Experience with Prototype
The test implementation is currently being compared to how unit checking is made in other tools.

## Required Patents
To the best of our knowledge, there are no patents that would conflict with the incorporation of this MCP.

## References
(None.)
