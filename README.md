# CSS `calc()` Miscalculation Bug

This repository demonstrates a bug where the CSS `calc()` function produces unexpected results when combining percentages and other units.  The issue is described in `bug.css` and a possible solution is provided in `bugSolution.css`.

## Problem
The expected calculation within `calc()` does not match the rendered output. This often happens when percentages are involved alongside fixed units (like pixels or ems).