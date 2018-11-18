# PS7
homework 7-econ628

The utility function is:

#---Household Problem

u(c,σ)= (c^(1-σ))/(1-σ) 

r=0.00 
The parameters are:

AiyagariModel = @with_kw (β=0.96,
    σ=1.1,
    α=0.33, 
    A=1,
    δ=0.05,
    z=[0.1; 1.0],
    p=[0.9 0.1; 0.1 0.9],
    a_min=1e-10,
    a_max=15,
    a_size=150) 
param = AiyagariModel()
