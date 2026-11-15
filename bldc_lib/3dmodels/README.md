# 3D models

Vendor STEP models are not redistributed in this repository. The board still
opens and renders without them; only the affected parts show no 3D body.

| Part | Reference | File expected here | Source |
|---|---|---|---|
| Molex Micro-Fit 3.0, 2-pin, right-angle | J4 (CAN) | `436500200.stp` | Molex product page for part number **43650-0200** (CAD models section) |

Download the model, save it in this folder with the file name shown above,
and KiCad will pick it up through `${KIPRJMOD}/../bldc_lib/3dmodels/`.
