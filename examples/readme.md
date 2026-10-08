# Road-image examples and potential inputs

This folder originally collected links to illustrative photographs of potholes and notes about candidate image features. It does **not** contain a labeled dataset or an executable detector.

## Example-image sources

The historical references below point to images on **external websites**. Availability and licensing have not been verified. Please view them at their sources and do not assume they may be downloaded, redistributed, or used for model training without permission.

- [Vale of Glamorgan pothole example](http://www.valeofglamorgan.gov.uk/Images/Vehicles%20and%20roads/Pothole.jpg)
- [North Carolina DOT pothole example](https://www.ncdot.gov/contact/report/pothole/images/pothole.jpg)
- [Wikimedia Commons pothole example](https://upload.wikimedia.org/wikipedia/commons/thumb/9/94/Pothole.jpg/640px-Pothole.jpg) — check the individual Commons file page for the applicable license and attribution.
- Older references also included news-site images; these have been removed from embedded previews to avoid presenting them as reusable dataset assets.

## Potential input signals (not validated features)

For images: surface color and texture, gradients, boundaries/contours, shape, camera perspective, road markings, shadow and lighting conditions.

For a future mobile or robotic sensing system: video temporal continuity, capture timestamps, camera calibration, and location metadata.

## What a future sample dataset would require

1. **Provenance and permissions:** Document where each image came from and the rights to reuse it.
2. **Labels:** Distinguish potholes, normal roadway, patches, shadows, and confusing negative examples.
3. **Train/validation/test separation:** Split by route, capture session, or physical location where possible to reduce leakage.
4. **Evaluation:** Report precision/recall, false alarms, localization quality (if relevant), and latency.
5. **Reproducibility:** Pin versions, provide a limited licensed sample and scripts, and document any unavailable data.

**Current status:** These are exploratory notes; no model training or inference is implemented in this folder.
