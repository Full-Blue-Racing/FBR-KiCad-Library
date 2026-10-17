# FBR KiCad Library
This repository contains symbols, footprints and 3D models for parts commonly used in FBR projects but are not included in the standard KiCad library. 

# To access FBR library from KiCad

**1. Clone this repo** into somewhere sensible (e.g. your Documents folder). Notice you have a `.kicad_sym` file for symbols and a `.pretty` folder for footprints.

**2. Add the symbol library**
- Open **Preferences → Manage Symbol Libraries**
- Pick the **Global** tab or **Project Specific** tab 
- Click the **+ icon** at the bottom left to add a row
- Set a **Nickname** and browse to the `.kicad_sym` file for the **Library Path**
- Click **OK**

**3. Add the footprint library**
- Open **Preferences → Manage Footprint Libraries**
- pick Global or Project tab, click **+**, give it a **Nickname**, and set the path to the `.pretty` **folder**

**4. Verify** — open the Symbol Editor or place a symbol; your new library should appear in the list by its nickname.

**Tips**
- Use the same nickname convention your team uses (handy for FBR if others pull the same project).
- Consider the **Project Specific** tab plus the `${KIPRJMOD}` path variable if you want the library to travel with the repo rather than living only on your machine.
