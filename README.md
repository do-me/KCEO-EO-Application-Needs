# KCEO-EO-Application-Needs

A quick visualisation of Earth Observation Application needs (work in progress) found in EU legislation and global conventions. Using https://apple.github.io/embedding-atlas.

<img width="1920" height="1085" alt="image" src="https://github.com/user-attachments/assets/7124f08b-439d-4aa3-951f-13d3194dce63" />

## Build static app 

Note that embedding-atlas might change the flag names if this command doesn't work. See the docs in case.

1. Run the local app

```shell
uvx embedding-atlas ANs_21_10_2025.parquet --duckdb server --no-embedding --text AN --x x --y y
```

2. Open http://localhost:5055 and modify the settings.
3. Export application from the settings section:

<img width="521" height="389" alt="image" src="https://github.com/user-attachments/assets/80ca87fb-1c32-4990-b03e-4f1833b2085b" />
