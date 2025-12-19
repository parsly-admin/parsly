The shared directory follows the same folder structure as the if it was a feature. In the same matter that features have their own components, hooks, types, etc. This will also follow does rules.
Only difference is that this specific directory can be accessed app wide.

---

Components: This is where we will store UI components that don't really have a feature they belong too. Things like Header.tsx, Footer.tsx, Dashboard.tsx, etc...
UI (Shadcn): Currently storing Shadcn components in here. Individual things like Button.tsx, Card.tsx, etc.

constants : App wide constants
types: App wide types

---

I know there can be a bit of a confusion since both components and UI contain UI Components.
But the key differences between the two is that one is for components that we build, and UI is for the components we install from Shadcn.
This is in an attempt to keep things organized a bit. But I am open to feedback as always.
