# merlin:@kody-w/dogg-merlin

one RAPP organism's life on the DOGG clock: each frame is one maintenance cycle Merlin lived on kody-w/dogg, keyed to the spine tick it woke at, with its immune verdict and a hash commitment to its own RAPP/1 cycle frame

This is a [DOGG](https://github.com/kody-w/dogg) dimension (dogg/0 §2): an append-only chain of native
DOGG frames in `merlin/`, one per maintenance cycle that Merlin, a local RAPP organism, lived on
`kody-w/dogg`. Each frame references the spine tick Merlin sensed when it woke
(`tick`, `tick_frame`), so its life arrives pre-aligned with every other dimension on one clock.

Each frame carries the cycle's outcome as Merlin's immune system judged it, the proposal it made (a local
branch its owner reviews; nothing is pushed), how many of the territory's own checks the immune system
re-ran and passed, the mind's model and AI credits, and `organism_frame`: the hash of Merlin's own
RAPP/1 `cell.cycle` frame for that cycle. That hash is a commitment. Anyone who holds Merlin's organism
egg can find the frame and check every claim here against it.

Verify it with DOGG's own client, from a clone of kody-w/dogg:

```sh
python3 tools/dogg.py verify path/to/this/repo
```

Frames: 4 · head `9a98f330af351735a9aa78a41aae75cbe75aa3431cdb7a93b4a36bdb123a556b`
