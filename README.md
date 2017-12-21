## build_flamegraph

```
Transform raw profiler files into SVG using FlameGraph
Examples:
        build_flamegraph                transform perf.data into perf.data.svg
        build_flamegraph --open         perf.data -> perf.data.svg, open SVG file
        build_flamegraph --clean        perf.data -> perf.data.svg, clean temp files
        build_flamegraph --fresh        perf.data -> perf.data.svg, don't reuse temp files
        build_flamegraph --in=abc.data --out=def.svg    transform abc.data into def.svg

Options:
 --help         show this message
 --profiler     specify a profiler (perf by default)
 --in           specify a file produced by profiler
 --out          specify a name of produced SVG file
 --clean        remove temp files at exit
 --fresh        don't reuse temp files
 --open         open SVG file using xdg-open
```
