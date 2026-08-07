# Outliers Second Brain - Layer 4 - Operations

You have assistants that can read your material, form a view, and write. They run when you ask,
in whatever order you happen to ask, with nothing standing between them and another person.

A system left running fails quietly by default. It carries on, reports success, produces nothing,
and there is nobody sitting beside you to notice.

## Install it

    python install.py

Add `--no-schedule` to install everything without putting the morning list on a timetable.

## What it needs beneath it

Layers 1 to 3. This layer arranges things that already work, so there has to be something to
arrange.

## What you end up with

| Thing | What it does |
|---|---|
| `_engine/today.py` | One short list each morning, ordered by what changed, each line saying why it is there |
| `_engine/ledger.py` | The record of what happened. Added to, never rewritten |
| `Areas/The gate.md` | The rule that nothing reaches another person without your hand on it |
| A timetable | The morning list runs on a clock, with no window and no interruption |

## Why it runs out of sight

A job that opens a window while you are working gets switched off within a week, and a job that
is off is a job that is not running. On Windows the timetable points at a launcher that runs the
work invisibly rather than at Python directly.

This is not a detail. It is the difference between automation you keep and automation you
disable.

## The gate

Anything intended for another person is written, checked by something other than the thing that
wrote it, and then stops. You send it.

It lives in the machinery rather than in an assistant's instructions, because instructions are
what a busy system stops reading first.

## What this layer leaves unsolved

Nothing further to install. What changes is that the system starts telling you things, and what
it tells you goes back down the ladder: a rule that keeps misfiring gets rewritten in Layer 2, a
source that never produces anything useful gets dropped in Layer 3.

The other thing that changes is what you can build on top. A foundation that remembers, keeps
itself honest, fills itself and runs without watching is the ground another system stands on.
