# Fiber laser cutting, fiber-delivered variant

Frame-accurate anatomy of a generic fiber-laser cutter. 34 seconds, 30 fps, 1,020 frames indexed 0-1019. One continuous side elevation. The camera moves. The machine is not pulled apart.

Open `index.html` and press Play. The picture at any frame index is a pure function of that index. `?frame=510` opens that frame paused. Space plays. Arrow keys step. Keys 1-5 jump segments.

This is an explanatory motion study, not a certified drawing, a simulation, a setup sheet, or a safety procedure. An open industrial cutting beam is a Class 4 laser hazard. No power, feed rate, pressure, or brand is shown.

## What the shots do

| Frames | Time | Shot |
| --- | --- | --- |
| 0-149 | 0-5 s | Source, delivery fiber, and head. The fiber still enters the head at the end. |
| 150-299 | 5-10 s | Head section. Collimator, focusing optic, protective window, schematic focus envelope. |
| 300-509 | 10-17 s | Nozzle. Coaxial assist gas, valve actuation, capacitive standoff. The focus stays in frame. |
| 510-749 | 17-25 s | Kerf, enlarged and slowed. Taper, heat-affected zone, dross, striations. Beam and gas still enter from the nozzle. |
| 750-1019 | 25-34 s | Pull back to the flatbed. Frames 960-1019 hold on the complete machine. |

Cyan is the pathway overlay, not visible light. The beam is near-infrared, about a 1 micrometer class. Gold is actuation or energy. Violet is sensing, or a state change in the metal. Dashed lines are diagrams. Hatched metal is a section. Near covers are omitted so the mechanism stays visible.

Inert gas only clears melt (fusion cutting). Oxygen can add heat on carbon steel (reactive fusion cutting). Air is used on some jobs. This page specifies none of them.

## Reference scope

Mechanism reference: [Laser Institute of America](https://www.lia.org/). LIA publishes the Handbook of Laser Materials Processing and the Guide to High Power Laser Cutting. This page was not checked page by page against those books. Camera moves, palette, cutaways, and timing are original illustrations.

## Repo

About: Frame-accurate anatomy of a generic fiber-laser cutter: doped fiber, head focus, assist gas, kerf, and gantry.

Topics: fiber-laser, laser-cutting, industrial-laser, technical-animation, manufacturing, engineering-education, canvas, motion-graphics, anatomy, lia

`index.html` and `README.md` keep the names GitHub Pages and GitHub require. The brief fixes this palette, so the page is not a seven-theme dashboard. The frame clock is hand-rolled. A motion library would fight the integer frame index.

The same clock, section camera, and three-accent overlay can explain another cutting process, such as waterjet or plasma, by replacing the head and the kerf. Do not carry laser-specific labels across.
