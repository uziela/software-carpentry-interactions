Unicellular Automates
=====================

(original assignment designed by Guillaume Moreau)


Design the following software with a pen and paper:

We want to model the behaviour of unicellular automates called "neuneu", when
put in a closed space, that we will refer to as "the loft". These unicellular
automates can fall into four categories, that will have slightly different
behaviour. Yet, the life cycle for the four categories is the same. This life
cycle is as follow:

  - moving: all "neuneus" can move around the loft, but not the same way.
  - eating: all "neuneus" eat and drink. Of course, they don't all have the
    same need in energy and don't eat the same type of food.
  - reproducing: if they have enough energy, "neuneus" can reproduce. This
    action yields a new "neuneu".
  - dying: if the energy of a "neuneu" is too low, it dies.

Foods and drinks
-----------------

Food in the loft can have different energy value. Each "neuneu" categories can
eat only certain type of food (some of those are cannibals, and can eat one
another). Food is introduced randomly in the loft, both at the beginning and
randomly afterwards.

Population in the loft
----------------------

It is the population of neuneu in the loft at once. This population varies,
when neuneu dies, or are born, or reintroduced in the loft.

The loft
---------

The loft is an ensemble of h*w squares. Only one neuneu can be on a square at
once (except when they are reproducing). Squares can contain food and drinks.
These can be consumed by a neuneu in the square.

The neuneus
------------

They fall in the following categories:

  - the erratics: they move randomly, eating what they find. They reproduce if
    they meet one another.
  - the ravenous: same behaviour as the erratics, but they look for the
    closest food supply to feed from.
  - the cannibals: same behaviour as the ravenous, but they sometime choose to
    eat the closest neuneu instead of the closest food supply.
  - the rabbits: they eat what they can when moving, but their main focus is
    to find a partner to reproduce.
  - this list is of course not comprehensive…
