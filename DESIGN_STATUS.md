# DESIGN_STATUS

This file tracks the project status and remaining tasks for the ESP32 development board.

Current status
- Schematic: complete
- PCB: in progress
- BOM: preliminary export from schematic exists
- Gerbers: not generated yet

Open tasks
- [ ] Finish PCB routing
- [ ] Validate and fix DRC issues
- [ ] Confirm footprint accuracy for connectors and passives
- [ ] Finalize BOM with manufacturer part numbers
- [ ] Generate fabrication outputs (Gerbers, NC drill, stackup notes)
- [ ] Export final schematic PDF and board views
- [ ] Create a release with final manufacturing files once the PCB is ready

Notes
- This repo is currently a WIP portfolio project.
- Keep all custom libraries and project files in the hardware/ folders so the design is reproducible.
- Use Git LFS for large 3D model or archive files when needed.
