# CheoICBSimulation

We conducted stochastic simulations employing a stochastic branching process to depict antigen accumulation during cancer progression and therapy intervention.
In each simulation step, cells that are antigenically neutral and belong to a lineage can proliferate at a rate of r1. The two daughter cells resulting from each division accumulate antigenic mutations at an overall rate of mut_rate. The number of generated mutations, denoted as m, is sampled from a Poisson distribution (Poisson(mut_rate)), and each antigen's antigenicity is drawn from an Exponential distribution. 
In the IHoM, when a cell acquires an antigenic mutation, it transforms into an immunogenic cell, while in the IHeM, it becomes an antigenic cell. Antigenic cells can proliferate at a rate of r1, and immunogenic cells can proliferate at a rate of r2.
Immunogenic cells have a death rate d and an immune escape probability escape_rate. Furthermore, we introduce cell competition in our simulations to regulate population sizes.
