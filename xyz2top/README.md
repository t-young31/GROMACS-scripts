# xyz2top
_Generation of GROMACS topology from a .xyz file using a GAFF forcefield_

Run with
```bash
python xyz2top.py test.xyz
```

If the charge and mutipliciy are not 0 and 1 respectively they may be specified with `-c` amd `-m` flags respectively
```bash
python xyz2top.py test.xyz -c 0 -m 1
```