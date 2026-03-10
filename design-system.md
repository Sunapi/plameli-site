# PLAMELI Website Design System

This file defines the layout and visual rules for the Plameli website.

All AI agents (Codex, Cursor, Copilot) must follow these rules when generating or modifying UI code.

The project uses:

Astro + Tailwind CSS

No React or other frameworks should be introduced.

---

# Layout System

## Container

All sections must use the same container.

Tailwind classes:

max-w-7xl mx-auto px-6

Never create custom container widths.

---

## Section spacing

Standard vertical spacing between sections:

py-24

Dense sections may use:

py-16

Spacing scale must follow:

4 / 8 / 16 / 24 / 32 / 48 / 64

Random margins are not allowed.

---

# Grid System

The website uses a 12-column layout.

Hero layout:

grid grid-cols-12 items-center gap-12

Left column:

col-span-12 lg:col-span-6

Right column:

col-span-12 lg:col-span-6

Card grids:

grid grid-cols-2 gap-6

---

# Typography Scale

Hero title:

text-4xl lg:text-5xl
font-semibold
leading-tight
max-w-xl

Section titles:

text-3xl
font-semibold

Paragraph text:

text-lg
leading-relaxed
max-w-lg

Small text:

text-sm
text-neutral-500

---

# Buttons

Buttons must follow this structure.

Primary button:

rounded-xl
bg-orange-500
text-white
px-6 py-3
hover:bg-orange-600
transition

Secondary button:

rounded-xl
border
border-neutral-300
px-6 py-3
hover:bg-neutral-100

Buttons should always be inside:

flex gap-4 mt-8

---

# Cards

Service cards must follow this structure:

rounded-2xl
bg-white
p-6
shadow-sm
border border-neutral-200

Card icon container:

w-10 h-10
rounded-lg
bg-orange-100
flex items-center justify-center

Cards should never overflow containers.

---

# Hero Composition

Hero layout must always follow this structure.

Container

grid grid-cols-12 items-center gap-12

Left column:

badge
hero title
paragraph
buttons

Right column:

service cards

Cards wrapper:

relative max-w-lg ml-auto

---

# Section Structure

Each section should follow this structure:

Section
Container
Section title
Section description
Grid or content block

---

# Layout Consistency Rules

AI agents must ensure:

• consistent spacing scale
• aligned containers
• balanced text width
• cards inside layout wrappers
• no overflowing elements
• no inline styles

Tailwind classes must be used for layout and spacing.

---

# Reference Design

The visual reference for the layout is the original v0 prototype located at:

D:\Dev\plameli-v0

AI agents should analyze that prototype to understand layout composition.

The current site content must remain unchanged.
