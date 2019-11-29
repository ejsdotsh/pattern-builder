# pattern-builder
a framework for defining "patterns" from the decomposed elements of a network design, and then rendering those patterns into:
- device configurations
- cable maps
- DNS updates
- etc.

## components
- RackBuilder
-- topology.yaml
- PodBuilder
-- N x RackBuilder
-- topology.yaml
- ZoneBuilder
-- N x PodBuilder
-- topology.yaml
- PopBuilder
-- N x RackBuilder
-- topology.yaml
