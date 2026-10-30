# Smart meter hardware design

This repository contains EasyEDA design documents for a smart electricity meter:

- `1-Schematic_alan babu.json` — schematic document.
- `1-PCB_PCB_alan.json` — PCB layout document.

There is currently no firmware, bill-of-materials file, calibration procedure, or cloud integration code in this repository. The designs should be reviewed and completed for the intended hardware before fabrication or use.

## Open the designs

1. Download or clone this repository.
2. In EasyEDA, use **File → Open → EasyEDA** (menu wording may vary by version).
3. Select one of the JSON files and import it into a project.
4. Review the schematic and PCB together, then run the editor's electrical-rule and design-rule checks before ordering a board.

## Safety

This project concerns mains electricity. Mains circuits can cause fatal shock, fire, or equipment damage. Do not connect or handle an energized circuit. Have the schematic, PCB clearances, isolation barriers, component ratings, fusing, enclosure, and applicable local safety requirements reviewed by a qualified person before fabrication or use. A software design-rule check does not establish electrical safety or regulatory compliance.

## License

The repository describes this project as MIT licensed, but no license file is currently included. Until a license is added by the copyright holder, permission to reuse or distribute the files is not clearly granted.
