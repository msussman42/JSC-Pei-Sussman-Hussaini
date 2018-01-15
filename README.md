# JSC-Pei-Sussman-Hussaini

The file directory tree at the end of this file shows  
different versions of the same code used to reproduce results 
in the Journal of Scientific Computing 
paper by C. Pei, M. Sussman, and M.Y. Hussaini.  At each leaf of the 
directory tree, there is a "F90" file and the results ("maxerror" file)
of running the program on a linux machine.

In order to build and run the program in each leaf:
1. gfortran -O filename.F90
2. ./a.out >& run.out &



DIRECTORY TREE:

.
├── directory_tree
├── Fig13
│   └── NEEFR-upwind
│       ├── Adv-Istable-NEEFR-upwind.F90
│       ├── maxerr010.dat
│       └── run.out
├── Fig15
│   ├── Coupling1
│   │   ├── EEFR
│   │   │   ├── average
│   │   │   │   ├── AdvDR-Istable-EEFR-av-coupling1.F90
│   │   │   │   ├── maxerr005-n080.dat
│   │   │   │   └── run.out
│   │   │   ├── upwind
│   │   │   │   ├── AdvDR-Istable-EEFR-up-coupling1.F90
│   │   │   │   ├── maxerr005-nup080.dat
│   │   │   │   └── run.out
│   │   │   ├── upwind2
│   │   │   │   ├── AdvDR-Istable-EEFR-up-coupling1.F90
│   │   │   │   ├── maxerr005-nup080.dat
│   │   │   │   └── run.out
│   │   │   ├── upwind3
│   │   │   │   ├── AdvDR-Istable-EEFR-up-coupling1.F90
│   │   │   │   ├── maxerr005-nup080.dat
│   │   │   │   └── run.out
│   │   │   └── upwind4
│   │   │       ├── AdvDR-Istable-EEFR-up-coupling1.F90
│   │   │       ├── maxerr005-nup080.dat
│   │   │       └── run.out
│   │   └── NEEFR
│   │       ├── average
│   │       │   ├── AdvDR-Istable-NEEFR-av-coupling1.F90
│   │       │   ├── maxerr005-nup080.dat
│   │       │   └── run.out
│   │       └── upwind
│   │           ├── AdvDR-Istable-NEEFR-up-coupling1.F90
│   │           ├── maxerr005-nup080.dat
│   │           └── run.out
│   └── Coupling2
│       ├── EEFR
│       │   ├── average
│       │   │   ├── AdvDR-Istable-EEFR-av-coupling2.F90
│       │   │   ├── maxerr005-o-a080.dat
│       │   │   └── run.out
│       │   ├── average10
│       │   │   ├── AdvDR-Istable-EEFR-av-coupling2.F90
│       │   │   ├── maxerr010-o-a080.dat
│       │   │   └── run.out
│       │   └── upwind
│       │       ├── AdvDR-Istable-EEFR-up-coupling2.F90
│       │       ├── maxerr005-o-u080.dat
│       │       └── run.out
│       └── NEEFR
│           ├── average
│           │   ├── AdvDR-Istable-NEEFR-av-coupling2.F90
│           │   ├── maxerr005-o-a080.dat
│           │   └── run.out
│           └── upwind
│               ├── AdvDR_Istable-NEEFR-up-coupling2.F90
│               ├── maxerr005-o-u080.dat
│               └── run.out
├── Fig16
│   ├── intrusive
│   │   ├── Coupling1
│   │   │   └── NEEFR
│   │   │       ├── average
│   │   │       │   ├── AdvDR-Istable-NEEFR-av-coupling1-intrusive.F90
│   │   │       │   ├── maxerr005-nav080.dat
│   │   │       │   └── run.out
│   │   │       └── upwind
│   │   │           ├── AdvDR-Istable-NEEFR-up-coupling1-intrusive.F90
│   │   │           ├── maxerr005-nup080.dat
│   │   │           └── run.out
│   │   └── Coupling2
│   │       └── NEEFR
│   │           ├── average
│   │           │   ├── AdvDR-Istable-NEEFR-av-coupling2-intrusive.F90
│   │           │   ├── maxerr005-o-a080.dat
│   │           │   └── run.out
│   │           └── upwind
│   │               ├── AdvDR-Istable-NEEFR-up-coupling2-intrusive.F90
│   │               ├── maxerr005-o-u080.dat
│   │               └── run.out
│   └── nonintrusive
│       ├── Coupling1
│       │   ├── EEFR
│       │   │   ├── average
│       │   │   │   ├── AdvDR-Istable-EEFR-av-coupling1-nonintrusive.F90
│       │   │   │   ├── maxerr005-n080.dat
│       │   │   │   └── run.out
│       │   │   └── upwind
│       │   │       ├── AdvDR-Istable-EEFR-up-coupling1-nonintrusive.F90
│       │   │       ├── maxerr005-nup080.dat
│       │   │       └── run.out
│       │   └── NEEFR
│       │       ├── average
│       │       │   ├── AdvDR-Istable-NEEFR-av-coupling1-nonintrusive.F90
│       │       │   ├── maxerr005-nav080.dat
│       │       │   └── run.out
│       │       └── upwind
│       │           ├── AdvDR-Istable-NEEFR-up-coupling1-nonintrusive.F90
│       │           ├── maxerr005-nup080.dat
│       │           └── run.out
│       └── Coupling2
│           ├── EEFR
│           │   ├── average
│           │   │   ├── AdvDR-Istable-EEFR-av-coupling2-nonintrusive.F90
│           │   │   ├── maxerr005-o-a080.dat
│           │   │   └── run.out
│           │   └── upwind
│           │       ├── AdvDR-Istable-EEFR-up-coupling2-nonintrusive.F90
│           │       ├── maxerr005-o-u080.dat
│           │       └── run.out
│           └── NEEFR
│               ├── average
│               │   ├── AdvDR-Istable-NEEFR-av-coupling2-nonintrusive.F90
│               │   ├── maxerr005-o-a080.dat
│               │   └── run.out
│               └── upwind
│                   ├── AdvDR-Istable-NEEFR-up-coupling2-nonintrusive.F90
│                   ├── maxerr005-o-u080.dat
│                   └── run.out
├── Fig7
│   ├── EEFR
│   │   ├── average
│   │   │   ├── Adv-Istable-EEFR-average.F90
│   │   │   ├── maxerr004-t160.dat
│   │   │   └── run.out
│   │   └── upwind
│   │       ├── Adv-Istable-EEFR-upwind.F90
│   │       ├── maxerr004-t160.dat
│   │       └── run.out
│   └── NEEFR
│       └── average
│           ├── Adv-Istable-NEEFR-average.F90
│           ├── maxerr004.dat
│           └── run.out
└── Fig8
    └── nonintrusive
        ├── EEFR
        │   ├── average
        │   │   ├── Adv-Istable-EEFR-average-nonintrusive.F90
        │   │   ├── maxerr004-t160.dat
        │   │   └── run.out
        │   └── upwind
        │       ├── Adv-Istable-EEFR-upwind-nonintrusive.F90
        │       ├── maxerr004-t160.dat
        │       └── run.out
        └── NEEFR
            └── average
                ├── Adv-Istable-NEEFR-average-nonintrusive.F90
                ├── maxerr004.dat
                └── run.out

59 directories, 94 files
