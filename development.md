## Development

### Git Commits

#### Commits

Each commit should have code that can execute and test coverage should be 100%.
The primary goal of a commit is comprehension. Smaller commits are prefereable,
but not to the point that the objective breaks down.

#### Style

Most commits will follow a minimal style. Starts with + or - for add/remove, !
for bug fix and ^ for performance improvement. Then the location of the change
down to the struct, method or function depending on the situation.

Additional comments can be added if there something worth noting, but the
expectation is that between documentation comments and tests, the change should
be reasonably self documenting.

#### Branches

Any branch starting with r_ is a release branch. History will not be changed
on these branches.

Branches starting with d_ are development branches. They may be broken up and
history may be rewritten.

Branches starting with x_ are experimental branches.