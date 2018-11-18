# PS7
homework 7-econ628

This is a simple Ayaghari model with state variables.

The utility function is:

u(c,σ)= (c^(1-σ))/(1-σ) 

The parameters are:

AiyagariModel = @with_kw (?=0.96,
    ?=1.1,
    ?=0.33, 
    A=1,
    ?=0.05,
    z=[0.1; 1.0],
    p=[0.9 0.1; 0.1 0.9],
    a_min=1e-10,
    a_max=15,
    a_size=150) 
param = AiyagariModel()

