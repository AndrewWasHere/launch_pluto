# Launch Pluto

Launch a Pluto.jl notebook from the command line, because I'm too lazy to type

```
cd [notebook directory]
julia
import Pluto
Pluto.run()
```

each time I want to work in a Pluto notebook.

## Use

To use, stick `pluto` in your path somewhere, then type:

    pluto [notebook directory]

Where

    notebook directory is the optional directory path to launch the Pluto 
    instance in.

Ctrl-C to exit Pluto, as usual.

## Dependencies

Julia, and Pluto.jl must be installed.

## Issues

Exiting Pluto results in an unhandled InterruptException in the Julia instance. 
I haven't figured out why this is happening. Using `julia -i -q` in the script 
didn't help.

## License

Public domain. Share and enjoy!

