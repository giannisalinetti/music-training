# Music Training
This repository contains private music training exercises and ideas. Its purpose is to keep track of my activities 
and ideas.

## Notation schema
This is my personal notation schema. I did not felt comfortable with ABC and just tried to develop mine.
The following is an INCOMPLETE schema that doesn't cover all the use cases.

## Metrics
We use an `N:D` pattern, like the following examples:
```
4:4 = 4/4 metric
6:8 = 6/8 metric
```

## Alterations
```
_ = flat
# = sharp
% = bequadro  
__ = double flat
## = double sharp
```

## Time notation
```
/2 = 1/2
/4 = 1/4
/8 = 1/8
/16 = 1/16
```
Odd groupings
```
/8[3] = 1/8 triplet
/8t = 1/8 triplet (short notation for triplets)
/8[5] = 1/8 quintuplet
/16[6] = sextuple
```

## Pauses
```
^ = pause
```

Pauses combine with time notation:
```
^/8 = 1/8 pause
```

## Repetitions
```
|: :|
```

## Guitar related notation
```
(s1) = first guitar string (E)
```

## Example line
The following example is a line played on guitar with YAML format:
```
data: |
4:4;(s4)b2/8,(s3)#d3/8,#f3/8,#d3/8,%d3/8,(s4)c3/8,a2/8,#a2/8,b2/8
```
