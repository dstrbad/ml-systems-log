# Four Months in ML Systems

A self-directed study log: ML compilers, GPU kernels, MLIR, and
the systems work that makes them fast.

Ride along with me if you like :)

## What this is

Four months of focused work on getting genuinely good at ML systems:
CUDA, Triton, MLIR, distributed GPU work, and whatever rabbit holes
the work opens up. The endpoint is to ship something real:
a kernel competition placement, a contribution to tinygrad or
another open-source project, or a measurable improvement on
something that matters. Whichever feels most alive by week six.

This is a public work log, not a tutorial.


## Phases

1. **Foundation refresh**: LLVM Kaleidoscope, C++ refresher, GPU MODE basics
2. **GPU fundamentals**: CUDA, PMPP, naive and tiled matmul, NSight profiling
3. **Triton entry**: Python-embedded GPU kernels, PTX inspection
4. **MLIR proper**: IR dialects, lowering passes
5. **First real contribution**: the centerpiece
6. **Synthesize**: Flash Attention, NCCL collectives, CUDA Graphs, second push


## Layout

```
/cuda     CUDA kernels, benchmarks, NSight reports
/triton   Triton kernels, PTX dumps, fused-op experiments
/mlir     MLIR Toy tutorial, dialect experiments, LLVM Kaleidoscope
/notes    Reading notes, paper summaries, lecture notes
/docs     The plan, references, anything reusable
```

## Following along

- Writeups on Substack: [dstrbad.substack.com](https://dstrbad.substack.com)
- Day-to-day on X: [@dstrbad](https://x.com/dstrbad)

If you're working through similar material, open an issue or
reach out. I'm not teaching, but I'm happy to compare notes.

## Reference stack

The work draws on:

- *Programming Massively Parallel Processors* (Hwu, Kirk, El Hajj) — the PMPP book
- [GPU MODE](https://www.youtube.com/@GPUMODE) lectures and Discord
- [Aalto Programming Parallel Computers](https://ppc.cs.aalto.fi/) — structured exercises
- [Triton](https://triton-lang.org/) and [MLIR](https://mlir.llvm.org/) official docs and tutorials
- *Systems Performance* (Brendan Gregg) — methodology reference
- [AI Performance Engineering](https://github.com/cfregly/ai-performance-engineering) (Fregly) — companion repo, 200-item performance checklist, monthly meetup videos
- [Convex Optimization](https://web.stanford.edu/~boyd/cvxbook/) (Boyd) — math reference

## Started

May 23, 2026.
