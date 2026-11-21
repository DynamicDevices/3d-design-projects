# SKÅDIS screwdriver-bit tray

A stepped tray for consolidating screwdriver bits, with individual upright hex
sockets and replaceable labels. Designed for Alex J Lennon with Briar's help.

## Design state

The approved reference is iteration 3. Iteration 4 is the current slimmer
comparison candidate; the geometry is preserved locally, not manufacturing-
or strength-accepted. This public record contains no model files yet: the
imported T-Clip interface requires primary-source licence verification.

Both versions retain forty blind sockets in five rows of eight, five slide-in
row labels, a long slide-in front label and separate SKÅDIS T-Clips. Provisional
sockets are 6.7 mm across flats with 10 mm insertion depth. Fit is untested.

| Feature | Reference, iteration 3 | Candidate, iteration 4 |
|---|---|---|
| Overall dimensions | 170 × 90 × 72 mm | 170 × 90 × 68 mm |
| Back support | Full rectangular backplate | Low rail with two rounded mounting ears |
| Underside | Deeper filled supports | Hollowed label-side support and shorter edge aprons |
| CAD solid volume | 202,330.60 mm³ | 119,469.36 mm³ |
| Sockets, labels and connector-seat centres | Reference | Preserved |

The candidate has approximately 41% less CAD solid volume. That is not a
filament-saving or strength claim. It also reduces mounting surround, making
structural verification important. The long front insert needs 156 mm of side
clearance to slide in/out, or the tray must be removed from the board.

## Printer and material

- Printer: Bambu Lab A1 Mini; 0.4 mm nozzle.
- Material: standard black PETG; supplier properties not yet established.
- Detailed print settings, orientation and supports: provisional, not released.

## Evidence and open checks

Preliminary FEA completed twelve idealised body solves using assumed fully solid,
isotropic PETG. Poor mesh quality prevents structural acceptance. The model
does not validate sparse infill, layer adhesion, creep, clips, board or anchors.

Four diagnostic slicing exports completed, but the effective machine profile
contained unsuitable start/end commands despite its A1 Mini name. Those exports
are not print-ready. Supports and support-removal access remain design concerns.

The screening payload was a 565 g mixed example group, not a measured forty-bit
capacity or measured per-socket loads. A separately weighed 480 g flexible
extension is not included in this tray. No safe-load rating is claimed.

Before model release: verify upstream rights, validate a trusted machine profile,
improve the mesh and complete appropriate design review. Before claiming a
successful print or safe use: test fit, support removal, access and loading.

## Licence and dependencies

DD's contributions: [CC BY-NC-SA 4.0](../../LICENSE-SCOPE.md).
Original connector geometry: Line Arc Line's
[SKÅDIS T-Clip System](https://www.printables.com/model/256896-skadis-t-clip-system).
See [third-party notices](../../THIRD-PARTY-NOTICES.md); its licence is not
overridden by DD's licence.

[Project metadata](project.json). Assisted-by: Briar.
