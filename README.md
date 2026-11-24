# Gerber_PCB1

PCB fabrication package (Gerber RS-274X + Excellon drill) for a **70 × 100 mm, 2-layer** board.

Exported from **EasyEDA Pro v4.1.105** on 2026-11-18 08:52:54.
Units: millimeters, coordinate format 4.5 (leading zeros omitted, absolute).

## Files

| File | Layer |
| --- | --- |
| `Gerber_TopLayer.GTL` | Top copper |
| `Gerber_BottomLayer.GBL` | Bottom copper |
| `Gerber_TopSilkscreenLayer.GTO` | Top silkscreen |
| `Gerber_BottomSilkscreenLayer.GBO` | Bottom silkscreen |
| `Gerber_TopSolderMaskLayer.GTS` | Top solder mask |
| `Gerber_BottomSolderMaskLayer.GBS` | Bottom solder mask |
| `Gerber_BoardOutlineLayer.GKO` | Board outline |
| `Gerber_DrillDrawingLayer.GDD` | Drill drawing (documentation only) |
| `Drill_PTH_Through.DRL` | Plated through holes (Excellon) |
| `Drill_PTH_Through_Via.DRL` | Plated through vias (Excellon) |
| `FlyingProbeTesting.json` | Flying probe test data (export contained no entries) |
| `PCB下单必读.txt` | EasyEDA ordering reference note |

## Fabrication notes

- 2-layer stackup, PTH only (no blind/buried vias).
- Drill files are Excellon format, units in millimeters.
- `Gerber_DrillDrawingLayer.GDD` is a drawing/documentation layer — do not send it as a manufacturing layer.
- `FlyingProbeTesting.json` was exported empty, so no probe test points are defined in this package.

## Reference

EasyEDA PCB ordering guide: <https://prodocs.lceda.cn/cn/pcb/order-order-pcb/index.html>

## License

No license is granted. All rights reserved by the author.
The design is published for reference only; manufacturing from these files is at your own risk.
