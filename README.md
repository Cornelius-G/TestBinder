# TestBinder
Project.toml in root contains only one package: Distributions.jl  
Project.toml in the "binder" folder contains: Distributions.jl and Plots.jl

Link to binder: https://gesis.mybinder.org/binder/v2/gh/Cornelius-G/TestBinder/a46cf5e450ac012ae8c12e21cd4dc29ba5d194e0?filepath=TestNotebook.ipynb

When trying to run "using Plots" it fails, meaning the Project.toml in the "binder" folder does not seem to be used but only the one in root.
