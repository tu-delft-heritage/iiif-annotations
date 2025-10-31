# IIIF Annotations

Repository used to publish IIIF Annotations that target IIIF resources on the [special collections website](https://heritage.tudelft.nl).

## OCR

The scripts in the following repository were used to create the OCR data:

- https://github.com/glenrobson/iiif2annos/tree/main

The command used:

```
python iiif2annos/ocr.py --lang nld --base-output-uri https://tu-delft-heritage.github.io/iiif-annotations/supplementing \
https://heritage.tudelft.nl/iiif/manifests/txf-18197/manifest.json data/supplementing/txf-18197
```

The motivation was changed from `commenting` to `supplementing`.
