# Sketch Figma Import Fidelity Report

### Figma
<img width="1128" height="933" alt="image" src="https://github.com/user-attachments/assets/c58b345a-60c4-4925-a9d0-064147f45590" />

.fig file (save local file)  
↓   
import

### Sketch
<img width="1777" height="1024" alt="image" src="https://github.com/user-attachments/assets/20349a28-211d-4fe1-9f5a-2ef4deaf2bc9" />


---

### Figma
<img width="1168" height="1012" alt="image" src="https://github.com/user-attachments/assets/c275be8a-ec54-4dd7-9ca4-aa663c70f20b" />

.fig file (save local file)  
↓  
import

### Sketch
<img width="1777" height="1024" alt="image" src="https://github.com/user-attachments/assets/dcfcf292-12c5-48f4-9bf4-061e37f2ee94" />


-----
## Initial Support Message:

Hi Sketch team,

I’m evaluating Sketch as a possible local-first replacement for Figma, using the Mac app and the .fig importer.

My use case is simple static diagram/layout work: text, simple vectors, transparent PNGs, icons, and frames. No prototyping or interactive behavior.

Import path:

* Figma → File → Save Local Copy…
* Sketch → open the resulting .fig file

The file imports and the overall layout is recognizable, but fidelity breaks down more than expected. Some areas appear softened/rasterized, the layer tree contains many image #### layers, and some content that appears to be simple text/vector material does not seem to remain cleanly editable.

I’ve put a minimal visual comparison here:

https://github.com/philcockfield/tmp/blob/phil-sketch/README.md

My question:

Is this expected behavior for larger .fig files with many embedded image assets, or should simple static text/vector/PNG diagram files import with higher editable fidelity?

I’m especially interested because Sketch’s local Mac workflow and one-off licence make it a compelling migration path from Figma. If this kind of import can preserve simple diagram/layout work reliably, Sketch becomes a serious option for moving ongoing work out of Figma while keeping an editable source.

If .fig import is not the best route, what workflow do you recommend for maximum editability and fidelity?

For example:

* .fig import
* frame-by-frame SVG export/import
* PDF/SVG hybrid
* another Sketch-supported migration path

Happy to provide the source .fig file or a reduced reproduction file if useful.

Thanks,
Phil
https://github.com/philcockfield/tmp/blob/phil-sketch/README.md

