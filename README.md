#About the Dataset

## Primary Ratio of Hydrogen Mass to Carbon Mass (Prim_MH_to_MC)

**Prim_MH_to_MC** represents the primary ratio of hydrogen mass to carbon mass in the fuel mixture.

## Calculation Steps

1. **Determine the number of atoms**:
   - Count the hydrogen atoms (H) and carbon atoms (C) in the fuel molecule.

2. **Calculate the total mass of hydrogen**:
   \
   `Mass of H = (number of H atoms) × (atomic mass of H)`  
   *Atomic mass of H ≈ 1 g/mol*

3. **Calculate the total mass of carbon**:
   \
   `Mass of C = (number of C atoms) × (atomic mass of C)`  
   *Atomic mass of C ≈ 12 g/mol*

4. **Compute the ratio**:
   \
   `Prim_MH_to_MC = Mass of H / Mass of C`

---

## Example for Ethylene (C₂H₄)

- **Number of H atoms**: 4  
- **Number of C atoms**: 2  

**Masses**:  
- `Mass of H = 4 × 1 = 4 g`  
- `Mass of C = 2 × 12 = 24 g`  

**Ratio**:  
`Prim_MH_to_MC = 4 / 24 = 0.1667`  

---

## Additional Definitions

- **Prim_H_to_C**: Ratio of hydrogen to carbon *atoms* in the primary fuel.  
  - Example:  
    - Ethylene (C₂H₄): `4 H / 2 C = 2`  
    - Propylene (C₃H₆): `6 H / 3 C = 2`  

- **Fuel**: Molar mass of the primary fuel.  
- **Mixture**: Molar mass of the mixture fuel.  

- **Sec_H_to_C**: Ratio of hydrogen to carbon atoms in the mixture fuel.  
- **Sec_fuel_Percent**: Percentage of the mixture fuel.  
- **MC_Sec_fuel**: Mass contribution or concentration of fuel.  

- **PAH**: Polycyclic aromatic hydrocarbons value.  
- **GRPAH**: Graduated PAH.  

![Diagram](media/image1.png){width="6.27in" height="7.83in"}
