# NEURON mod files for K currents

From the paper:
Lien, et al., Gating, modulation and subunit composition of voltage-gated K(+) channels in dendritic inhibitory interneurones of rat hippocampus. *J Physiol.* 2002 538:405-19.

Running the `kinetics.hoc` simulation file will show:
- The activation and inactivation steady-states
- The time constants
- A family of curves generated modeling the same protocols used for Figs.5A-6A-7A of the paper

Markers show a few of the experimental values for the time constants derived from Figs.5C-6C-7C-7D.

For both the fast and slow KDR currents, an inactivation time constant of 1 sec is assumed. KA recovery from inactivation is not implemented.

---

## Instructions for compilation and running

### Under Unix systems:
To compile the mod files use the command:
```
nrnivmodl
```
Run the simulation hoc file with the command:
```
nrngui kinetics.hoc
```

### Under Windows:
To compile the mod files use the **mknrndll** command.
A double click on the simulation file `kinetics.hoc` will open the simulation window.

---

Questions on how to use this model with NEURON should be directed to [michele@pa.ibf.cnr.it](mailto:michele@pa.ibf.cnr.it).

---

2025-05-27 – Standardized to Markdown.