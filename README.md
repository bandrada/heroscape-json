# Heroscape JSON

Heroscape data in JSON format for use in Heroscape related projects.

## Background

This project was forked from [https://github.com/jesseflorig/heroscape-json](https://github.com/jesseflorig/heroscape-json) commit `7c71f8b` in order to be expanded upon. 

## Units
```
{
  name        \\ Unit name
  general     \\ General the unit falls under
  race        \\ Unit race
  type        \\ Squad or Hero
  class       \\ Unit class
  personality \\ Unit personality
  height      \\ Unit height
  life        \\ Unit hit points
  move        \\ Unit movement per turn
  range       \\ Unit attack range
  attack      \\ Number of attack dice
  defense     \\ Number of defense dice
  points      \\ Unit poiint value
  figures     \\ Number of figures
  hexes       \\ Number of hexes each figure takes up
  set         \\ Set the unit was released
  abilities: [
    {
      name          \\ Ability name
      description   \\ Ability description
    }
  ]
}
```

## Sets
```
{
  name          \\ Set name
  alternateName \\ Alternate set name
  type          \\ Set type
  universe      \\ Set universe
  released      \\ Date of release
}
```

## Glyphs
```
{
  name         \\ Glyph name
  power        \\ Glyph power
  description  \\ Description of power
  duration     \\ Permanent or Temporary
  sets         \\ Sets the glyph is from
}
```

## Generals
```
{
  name       \\ General name
  alignment  \\ Army alignment
  set        \\ Set the general was released
}
```
