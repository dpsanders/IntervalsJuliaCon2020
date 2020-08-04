# Calculating with sets: Interval methods in Julia

## Workshop at JuliaCon 2020

These are materials for the live, online workshop "Calculating with sets: Interval methods in Julia
" at JuliaCon 2020,
which will take place on Monday 27 July, 2020 at 2pm UTC.

For access, please register for a free ticket at https://juliacon.org/2020


## Setup

- Install the latest release (1.4.2) of Julia from [here](https://julialang.org/downloads/)

- Run Julia. At the Julia prompt, add the packages we will need as follows (copy and paste):

        julia> using Pkg

        julia> Pkg.add("IJulia")
        julia> Pkg.add("Plots")
        julia> Pkg.add("Interact")
        julia> Pkg.add("IntervalArithmetic")
        julia> Pkg.add("IntervalRootFinding")
        julia> Pkg.add("IntervalConstraintProgramming")
        julia> Pkg.add("IntervalOptimisation")


- Once those packages have finished installing (which will install a collection of other packages that these depend on), type

        julia> using IJulia
        julia> notebook()

  This should launch the [Jupyter notebook](https://jupyter.org) in your browser; this is a web application that provides a computational notegbook interface.

- Copy the notebook files (ending in `.ipynb`) from this repository to your computer by `git clone`-ing the repository or downloading the Zip file
(hit the green button which says `Code`).


- Navigate inside the file browser in the Jupyter notebook to the place on your computer where the files you just downloaded are. Load notebook number 1!

## Installation problems

- If you have installation problems you can also view the notebooks online at [nbviewer](https://nbviewer.jupyter.org/github/dpsanders/IntervalsJuliaCon2020/tree/master/) and use e.g. the online service [repl.it](https://repl.it) to write Julia code.

- If you are on the live call, you can try to describe your problem and ask for help via the chat; hopefully other attendees will be able to assist.


## License

Code in this repository is licensed under the MIT license, and text under the [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0) license. Copyright David P. Sanders 2020

## Author

David P. Sanders, Department of Physics, Faculty of Sciences, Universidad Nacional Autónoma de México (National University of Mexico, UNAM) & Department of Mathematics, MIT.
