# Russells-Approximation-Method--RAM-
 A method for solving Transportation Problem

Russell's Approximation Method (RAM):
Step-1:	For each source row still under consideration, determine its Ui (largest cost in row i).
Step-2:	For each destination column still under consideration, determine its Vj (largest cost in column j).
Step-3:	For each variable, calculate Δij=cij-(Ui +  Vj).
Step-4:	Select the variable having the most negative Δ value, break ties arbitrarily.
Step-5:	Allocate as much as possible. Eliminate necessary cells from consideration. Return to Step-1.

Source: https://cbom.atozmath.com/example/CBOM/Transportation.aspx?he=e&q=ram
