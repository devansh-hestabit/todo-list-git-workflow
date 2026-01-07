# Merge Conflict Postmortem

## What happened
Two clones modified the same line in todo.txt.

## Why conflict occurred
Git could not automatically merge changes to the same line.

## Resolution
Both changes were preserved manually.

## Evidence
![Commit graph showing merge and branches](screenshots/commit-graph.png)
