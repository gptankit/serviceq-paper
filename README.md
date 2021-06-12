# Adaptive Request Modeling in Clusters during Adverse States - White Paper

## Abstract

A distributed system consists of multiple nodes that share incoming load among themselves. In a centrally
coordinated environment, the responsibility falls on a gateway to manage request dispatch to this cluster of
nodes. In this paper, we propose an adaptive and unified approach to request dispatch to enhance decision
making capabilities of such a gateway in case of partial and total cluster shutdown states. Using the described
algorithms as a base, we derive a formula for landing probability on a node and explore its implication on
various cluster states. We also show, via graphs, the request dispatch pattern when using this approach with
adverse cluster states.

## Link to implementation

https://github.com/gptankit/serviceq
