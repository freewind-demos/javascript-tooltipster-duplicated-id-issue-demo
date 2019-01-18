JavaScript tooltipster Duplicated ID issue
==========================================

```
npm install
open index.html
```

If you put mouse on Link1 or Link3, there will be a popup as expected.

But put on Link2, there's nothing happens.

---

Fix: use my own fork which changed the code to work-around this issue:

<https://github.com/freewind/tooltipster/commit/dbdab7505181e0a6d49bc5d3e0fa286f541908de>

Change dependency `tooltipster` to:

```
"tooltipster": "freewind/tooltipster"
```
