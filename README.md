# KCEO-EO-Application-Needs

**APP with presets: [here](https://do-me.github.io/KCEO-EO-Application-Needs/#?H4sIAAAAAAAAE3VTXU/jMBD8K6d9Nr2kSZrUb1CKhAQVUoEXVFVuvA0Wjm3ZDm2v8n8/uV/QCl5saWc9Ozvr3cInWie0AgpJL017CRDwokXnWWuApuUgTYoyT7NeUlYEPgWugG7BvevVuF0g50I1QL3tkOyCz2whEeiSSXeITAXHBbPHpFrLrlVTv5HoItP1JJ5cOCPZBigsOykhEPAbg+fIgvEGI7Q+j78LzlFFYPMbcHf/MJ5Prh/HvyXMrV7NheK4/rFmIOBQYu2Rj5jHRtvNaNcH0L1QAnh041Xg6lFzBApGC+UdEGiFEm3X3qJywm/Ga3PHaq8t0IRA59DeMvuxf6M6KQMBI7V3QN+2IDhQKFmRpP9u2PO6HLxWuxH5aDNMWIv8z3SnTWgVazmDdWyi1q3RCpUHCqeEB+E8EDBWm+h+CIEcSry0N3kzepELP1Kl+Fbi0N9PtCPdKf8k9XdKWAqU/PguhDDbdzP1zO8nfnLq6vib4m203efEwBroVdJL0qQs+nmeZYNhlabDvNiNOCJFVmZlWRRVllVlnuUEXM2i3LTXT4bpsBr0q2GSVFlVBgKWqQZPHpxMvnCVbkF4bKPts695P1nkot5rf5sFcmlUXIZzZgK4Nkxx5Kc9MGhrVJ41x9UI5MKGvxIbVPyLDvn9UUwI4T/Li7lrqAMAAA==)**

**APP without presets: https://do-me.github.io/KCEO-EO-Application-Needs/**

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
