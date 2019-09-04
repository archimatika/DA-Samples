# Facade Toolkit

A work in progress prototype. Set of grasshopper definitions that allows to generate facade patterns and generate BIM model, based on prescripted rules.

## Methodology

Limits, that put demand on facade, are based on simple premitives (on early dev stage) and Architectural Model IfcEntities:

| Model element         |                                |
|-----------------------|--------------------------------|
| Breps                 | Massing model allow to define facade surface              |
| IfcSpaces             | Rooms that define extra properies for facade panel    |
| IfcColumns            | Structural elements as limits  |
| IfcWalls              | Walls as limits                |
| IfcFurnishingElement  | Furnishing element (kitchen cabinets, storage, ect) as limits |

## Used grasshopper compenents and libraries

- Telepaty
- Human
- HumanUI
- Metahopper
- Speckle
- Slingshot