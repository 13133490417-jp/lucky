# Boiler models V2: repaired OPC package

Download **boiler_models_v2.zip**. The V1 archive has been superseded.

V1 MATLAB error: `No content type was found for part: /_rels/.rels`.
V2 restores the default XML namespaces used by the original SLX and
explicitly declares content types for every OPC relationship part.

Recommended: extract V2 into a NEW folder, select that folder as the MATLAB
current directory, and run:

```matlab
start_here
```

This uses ordinary MATLAB construction scripts with Simulink add_block,
add_line and save_system to generate/open the two `_rebuilt.slx` models.
No MATLAB Function blocks are added. Then run `run_demo(true)` for the
actual MATLAB/Simulink validation, which was unavailable in the cloud.

The archive also contains the repaired direct SLX files, original backup,
IF97 tables and documentation. Parameters remain demonstrations, not plant
identification results or operating limits. See README.md inside the ZIP.

Archive bytes: 1439264
SHA256: b5da9ce16fd29b402ab67f42f7c4a09503640e0b93d9f5c51a43ce8d64e80e9d
