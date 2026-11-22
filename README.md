# Regen Guide

A college-level, hyperlinked guide to **Regen**, a declarative, knowledge-based generative programming environment built around Common Lisp, generative objects, attributes, composition, and design intent.

## Read the guide

Open [index.html](index.html) locally, or enable GitHub Pages from the repository's `main` branch and root (`/`) folder.

- [Start / contents](index.html)
- [Chapter 1: Generative Objects](chapters/01-generative-objects.html)
- [Chapter 2: Attribute Kinds and Object Protocols](chapters/02-attribute-kinds-and-object-protocols.html)
- [Chapter 3: Defining Generative Objects](chapters/03-defining-generative-objects.html)
- [Chapter 4: Spatial Organization](chapters/04-spatial-organization.html)
- [Chapter 5: Graphics in Generative Objects](chapters/05-graphics-in-generative-objects.html)
- [Chapter 6: Configurations](chapters/06-configurations.html)
- [Terminology index](glossary.html)

The HTML is static and has no dependencies or build steps. Relative links work locally or under a GitHub Pages project path.

## Editorial scope

The intended audience already knows Common Lisp. Early chapters develop concepts before showing concrete `defobject` syntax. This avoids claiming syntax or runtime behavior that hasn't been verified against Regen.

Distinguish implemented Regen behavior from prospective features. Parameter/constraint solving and transactional recovery are future topics, **not** claimed as current implementations.

### Chapters and planned progression

1. Generative Objects
2. Attribute Kinds and Object Protocols
3. Defining Generative Objects with `defobject` (introductory examples grounded in Adhoc source patterns)
4. Spatial Organization with `node-mixin` (examples grounded in adhoc-scene-graph and 3d-math; selected spatial examples verified in a running image)
5. Graphics in Generative Objects (shaft-and-support example with screenshot)
6. Configurations (dynamic component types; solid and hollow shaft example)
7. Attribute evaluation, explicit assignments, and invalidation (planned)
8. Object composition and dependency graphs (planned)
9. Advanced reference systems and geometry (planned)
10. Consistency, error recovery, and prospective transactions (planned)
11. Protocols and external implementations (planned)
12. Declarative modeling, design intent as a first-class concept, and knowledge-based engineering (planned)
13. Knowledge representation, ontologies, and schemas (distinguishing related concepts without treating them as a strict subset hierarchy)

## Structure

- `index.html`: landing page and contents
- `chapters/`: chapter pages
- `glossary.html`: alphabetical terminology index, linked to explanatory sections
- `assets/site.css`: layout, navigation, accessibility, typography

## Contributing

Use issues or pull requests for terminology corrections, examples, and proposals. Claims about concrete Regen implementation details should cite or be checked against the relevant source.

No external fonts, JavaScript libraries, or network requests are required.
