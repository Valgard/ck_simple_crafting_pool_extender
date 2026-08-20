# Simple Crafting Pool Extender

Plumbing for other mods. On its own it adds nothing you can see — install it
only because something else lists it as a dependency.

Vanilla workbenches have room for exactly three crafting tabs. A mod that needs
a fourth does not get an error message: the recipe registers and then simply
never appears, with only a line in the log to say so. This raises the ceiling
to five and fixes the paging arrows that go with it.

Applies to the Iron, Wood and Copper Workbenches, the Carpenter's Table, the
Forge and the other Simple-Crafting stations. Benches using one to three tabs
are untouched, and unused slots stay hidden exactly as before.

## For mod authors

List **SimpleCraftingPoolExtender** as a required dependency in your
ModBuilderSettings and mod.io prompts players to install it. Without it your
recipe renders only for players who happen to run another pool-expanding mod.
