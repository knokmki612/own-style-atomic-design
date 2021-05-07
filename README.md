# Own Style Atomic Design

## Atom

The minimal unit UI component.

1 to 1 between appearance and operation (ex: onClick, onChange events), as like `<button></button>` or `<input>`.

## Molecule

The UI component assembled by **Atom** or **Molecule**, or _n_ to _n_ between appearance and operation.

But can't establish independ UI by itself in the page except to depend on Organism.

## Organism

The UI component assembled by **Atom** or **Molecule** or **Organism**, or _n_ to _n_ between appearance and operation.

And can establish independ UI by itself in the page.

## Template

The UI component assembled by **Atom** or **Molecule** or **Organism**.

And equal the page itself.
