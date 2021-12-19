# Bayer Free State Court Record
The Court record for all criminal/civil cases in Bayer Free State

## Structures
- **Reference code:** including four-character year, underscore, and four-character index number counting up and reset to 0 for each year. Example: `2021_0001`.
- Each case should have a folder with the reference code, consist of:
    - `record.md` contain all of the notes relate to the court.
    - Exhibits: naming `exhibits-<number>-<character>.<ext>`
        - `<number>` starts from 0, counting up according the Court session
        - `<character>` starts from "A", counting up if exhibit was present toghether
        - `<ext>` appropiate file extention