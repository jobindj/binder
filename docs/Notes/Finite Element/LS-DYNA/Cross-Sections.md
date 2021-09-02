# Cross Sections

Cross sections can be defined in [[LS-DYNA]] in two ways:

- using node set and element sets
- using Plane

The cross-section can be kept persistent with respect to the model by defining it using node and element sets

## Output

Forces and Moments outputs are controlled using `*DATABASE_SECFORCE`

## Extract Node/Element Sets from Plane

The nodes and elements that are selected by solver are outputted to `d3hsp`. It can be found under `interface definition` (Source: [dynasupport](https://www.dynasupport.com/howtos/general/cross-section))


Template to convert `d3hsp` output to sets

```
*SET_NODE/BEAM/SHELL/SOLID_TITLE
$# title
Title for set
$#     sid      
      10001
 ````