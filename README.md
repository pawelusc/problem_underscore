Names in ctnumbers that include '_' are causing problems.

To reproduce run
```
theodore analyze_tden
theodore plot_om_bars
pdflatex Om_bars.tex
```

The `.tex` file reports double subscript error.
```
! Double subscript.
\tick ->$uhfref_1_
                  1$
l.84 \end{axis}
```
