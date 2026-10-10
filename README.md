# Ship Hull Stability & Metacenter Analyzer

Computes initial transverse stability for a simplified box hull including KB, BM, KM, and GM, with an SVG cross-section diagram and linearised GZ righting-lever curve.

## Key Features

- Inputs: Beam B, Draft T, Length L, Block coefficient Cb, and VCG (vertical centre of gravity from keel)
- Computes KB = T/2, BM = B²/(12·T·Cb), KM = KB+BM, GM = KM−VCG, and displacement
- Color-coded stability classification: Stable (GM > 0.15 m), Marginal (0–0.15 m), Unstable (GM ≤ 0)
- SVG cross-section sketch showing keel, waterline, B (buoyancy centre), G (gravity centre), and M (metacentre) with GM distance
- SVG GZ righting-lever curve (0–45°, linearised GZ = GM·sin θ) with color-coded fill
