# Patent Application: Parametric Geometry Fabrication Device

## Full Title
**Compact Manual or Solar Powered System for Generating Parametric Three-Dimensional Mathematical Models**

**Inventor:** Dr. Milan Amrut Joshi
**Filing Date:** [To be filed]
**Classification:** B29C 64/106 (Additive manufacturing); G09B 23/04 (Models for mathematical education)


---

## Abstract

A compact, portable device that generates three-dimensional physical models of mathematical surfaces, solids, and geometric constructions from parametric equations, function definitions, or geometric specifications input by the user. The device accepts mathematical input through a touchscreen interface or voice commands, computes a 3D mesh from the parametric definition using an on-board geometry engine, and fabricates the physical model using a novel low-temperature thermoplastic extrusion system or paper-lamination mechanism. The device can operate on solar power (for paper-lamination mode) or standard power (for thermoplastic mode), making it suitable for classroom and field use. Applications include: creating physical models of quadric surfaces (ellipsoids, hyperboloids, paraboloids), topological objects (Mobius strips, Klein bottles, tori), function plots (z = f(x,y) surfaces), fractals (Sierpinski pyramids, Menger sponges), and geometric proof models.


---

## Field of the Invention

This invention relates to mathematical model fabrication, specifically to compact systems that convert parametric mathematical definitions into three-dimensional physical objects for educational purposes.


---

## Background and Prior Art

### Problems with Current Approaches
1. Standard 3D printers require CAD expertise, are not portable, and cost $200-$2000+.
2. No device directly accepts mathematical equations as input and produces physical models.
3. Classroom math models are pre-made, expensive, and limited to common shapes.
4. Students cannot create custom physical models of the specific functions they are studying.

### Prior Art
- Consumer 3D printers (Prusa, Ender, Bambu) - Require STL files from CAD software
- Mathematica 3D printing export - Requires Mathematica license ($350+) and separate printer
- GeoGebra 3D export - Generates STL but requires separate printer
- Educational model kits (Zometool, Polydron) - Pre-defined shapes only

### Gap
No **compact, classroom-ready device** directly converts **parametric equations into physical 3D models** without requiring CAD software.


---

## Summary of the Invention

1. **Mathematical Input Interface:** 7-inch touchscreen with equation editor supporting parametric (x(u,v), y(u,v), z(u,v)), implicit (F(x,y,z)=0), and explicit (z=f(x,y)) surface definitions. Voice input for equation dictation. Preset library of 100+ famous mathematical surfaces.

2. **Geometry Engine:** On-device mesh generation:
   - Parametric surface tessellation with adaptive resolution
   - Implicit surface extraction via Marching Cubes algorithm
   - Boolean operations for constructive solid geometry
   - Automatic support structure generation
   - Scale-to-fit within build volume

3. **Fabrication System (Dual Mode):**
   - **Mode A - Thermoplastic:** Low-temperature PLA extrusion (180C) with 0.3mm layer height, build volume 80x80x80mm, 15-60 minute print time
   - **Mode B - Paper Lamination:** Solar-compatible paper cutting and stacking, build volume 100x100x50mm, under 3W power

4. **Power:** 12V DC adapter (Mode A) or integrated 5W solar panel + battery (Mode B)

5. **Size:** 250x250x300mm (approximately the size of a large textbook)


---

## Detailed Description

### Mathematical Input
- Equation editor with Greek letters, operators, 2D rendering
- Real-time 3D preview as equation is entered
- Parameter sliders for interactive coefficient adjustment
- Voice: "Create a torus with major radius 3 and minor radius 1"

### Input Modes
- **Parametric:** x(u,v), y(u,v), z(u,v) with domain specification
- **Implicit:** F(x,y,z) = 0 isosurface
- **Explicit:** z = f(x,y) with domain bounds
- **Preset Library:** 100+ surfaces organized by category:
  - Quadric surfaces (8): sphere, ellipsoid, hyperboloid, cone, cylinder, paraboloid
  - Topological objects (6): torus, Mobius strip, Klein bottle, trefoil knot
  - Minimal surfaces (5): catenoid, helicoid, Enneper surface
  - Fractals (8): Sierpinski, Menger, Koch, Hilbert, Mandelbulb
  - Platonic and Archimedean solids (18)
  - Geometric proof models (20+)

### Geometry Engine Pipeline
1. Parametric tessellation or Marching Cubes extraction
2. Mesh processing: normals, repair, smoothing, decimation
3. Support structure generation for overhangs over 45 degrees
4. Layer-by-layer slicing
5. Toolpath generation

### Fabrication
- **Mode A:** PLA 1.75mm, 0.4mm nozzle, 40mm/s, snap-in cartridge
- **Mode B:** Pre-cut adhesive A6 paper, precision blade on XY gantry, multi-color possible
- Processor: Allwinner H616 (quad-core Cortex-A53)


---

## Claims

### Independent Claims

**Claim 1.** A mathematical model fabrication device comprising:
(a) a touchscreen interface accepting mathematical surface definitions in parametric, implicit, or explicit equation forms;
(b) an on-device geometry engine that converts mathematical definitions into three-dimensional mesh representations;
(c) a fabrication subsystem that produces physical three-dimensional models from said mesh representations;
(d) wherein the device directly converts mathematical equations into tangible physical objects without requiring external CAD software.

**Claim 2.** The device of Claim 1, wherein the geometry engine supports parametric surface tessellation, implicit surface extraction via Marching Cubes, and constructive solid geometry boolean operations.

**Claim 3.** The device of Claim 1, further comprising a preset library of mathematical surfaces including quadric surfaces, topological objects, function plots, and fractals.

### Dependent Claims

**Claim 4.** The device of Claim 1, wherein the fabrication subsystem operates in dual modes: a thermoplastic extrusion mode using standard power and a paper lamination mode compatible with solar power.

**Claim 5.** The device of Claim 1, further comprising voice input for equation dictation and natural language surface specification.

**Claim 6.** The device of Claim 1, wherein the touchscreen displays a real-time 3D preview of the mathematical surface as the equation is entered.

**Claim 7.** The device of Claim 1, wherein the geometry engine automatically generates support structures for overhanging regions.

**Claim 8.** The device of Claim 1, wherein the geometry engine employs adaptive tessellation that increases resolution in regions of high curvature.

**Claim 9.** The device of Claim 4, wherein the paper lamination mode operates at less than 3W total power consumption.

**Claim 10.** The device of Claim 3, wherein the preset library includes geometric proof models that physically demonstrate mathematical theorems.


---

## Drawings Description

- **Figure 1:** Device perspective view showing touchscreen, build chamber, and filament cartridge
- **Figure 2:** Equation editor interface with 3D preview panel
- **Figure 3:** Geometry engine pipeline flowchart
- **Figure 4:** Mode A (thermoplastic) cross-section
- **Figure 5:** Mode B (paper lamination) cross-section
- **Figure 6:** Gallery of fabricated mathematical models
- **Figure 7:** Preset library browsing interface
- **Figure 8:** Solar panel integration for Mode B

---

*Patent Application Prepared by Dr. Milan Amrut Joshi*
