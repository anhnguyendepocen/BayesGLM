 x_.design_info.slice("c[T.c]")
 maybe priors are specified like:
   iid_priors=Normal(0,10)
   iid_priors=Uniform(5,15)
 "y ~ x1 + x2"
 {"x1": Uniform(5, 15)}
 {"x2": Normal(0,10)}
 {"cat1": Normal(0,1)} - refers to all
 {"1": (constant term)
 nothing: uniform improper
 can we include all supported priors in the loop to have fewer models?