# DLV Programs and Outputs

## Example 1

```dlv
% Some facts for the record_label rule
contracted_with(bocelli, universal).
contracted_with(james_brown, universal).
contracted_with(anderson_paak, sony).
contracted_with(jbs, sony).

% Facts to make cautious and brave approach give different results
contracted_with(queen, universal) v contracted_with(queen, sony).

contracted_with(X, Y)?              % differences in brave / cautious
% contracted_with(queen, Y)?          % differences in brave / cautious

% brave output:
DLV [build BEN/Dec 16 2012   gcc 4.6.1]

bocelli, universal
james_brown, universal
anderson_paak, sony
jbs, sony
queen, universal
queen, sony

% cautious output
DLV [build BEN/Dec 16 2012   gcc 4.6.1]

bocelli, universal
james_brown, universal
anderson_paak, sony
jbs, sony
```

## Example 2

```dlv
% Some facts for the record_label rule
contracted_with(bocelli, universal).
contracted_with(james_brown, universal).
contracted_with(anderson_paak, sony).
contracted_with(jbs, sony).

% Facts to make cautious and brave approach give different results
contracted_with(queen, universal) v contracted_with(queen, sony).

% contracted_with(X, Y)?              % differences in brave / cautious
contracted_with(queen, Y)?          % differences in brave / cautious

% cautious output:
DLV [build BEN/Dec 16 2012   gcc 4.6.1]

% brave output:
DLV [build BEN/Dec 16 2012   gcc 4.6.1]

universal
sony
```
