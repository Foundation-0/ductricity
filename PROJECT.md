# Project definition

## The device in one paragraph

Fluid enters a duct through a wide mouth. The duct narrows and speeds the flow up. Part of the wall in the narrow section moves: it sheds eddies into the flow, flexes, or turns. That same moving wall drives a generator, or carries a surface that turns flow into charge directly. The wall shapes the flow and extracts from it. One surface, both jobs.

## Why this is a separate problem

Existing devices split the two jobs.

- A wind lens or ducted turbine uses smooth fixed walls to shape the flow, and a separate rotor inside to extract.
- A vortex or flutter harvester uses a moving surface to extract, out in open flow, with no duct shaping the flow around it.
- A hydrovoltaic panel uses a fixed charged wall to extract from water at small scale, with no flow shaping.

No published device found in the parent project survey does both jobs with one surface.

## The central conflict

Extraction at a wall wants contact and resistance. A duct wants low resistance, so the flow does not stall or divert around the mouth.

Every design in this project is a proposed settlement of that conflict. A design that cannot state its settlement in one sentence is not ready to build.

Candidate settlements:

- Time sharing. The wall is smooth while flow builds, then moves in pulses to shed eddies and extract, then returns to smooth.
- Space sharing. Most of the wall stays smooth. Short active sections extract, spaced so the flow recovers between them.
- Eddy mediation. The wall shapes the flow so eddies form away from the wall, and a second surface inside the eddy zone extracts. The wall shapes, the eddies carry, the inner surface takes.
- Rotation. The wall section turns, as in a drum or a set of discs. A turning wall has low net resistance in the flow direction and still takes work from particle contact.

## Candidate mechanisms for the moving wall

### Oscillating wall sections

Panels in the duct wall, hinged or flexibly mounted. The flow sheds alternating eddies off each panel. The panel swings with the eddies and drives a small generator at its mount.

Risk: the device works only in the flow speed band where the panel swings in step with the eddies. Published vortex devices share this limit.

### Flutter membranes

A flexible film fixed at both ends inside the duct, coated with a piezoelectric layer, a layer that makes voltage when bent, or a triboelectric layer, a layer that makes charge when surfaces touch and part.

Risk: published flutter devices produce milliwatts. The membrane is cheap and has no bearings, so it may still win on cost per device for sensors.

### Rotating wall: discs and drums

A stack of smooth discs that the fluid drags around by viscosity, the drag between fluid layers. Or a drum whose outer surface is the duct wall itself.

Risk: measured efficiency for this transfer is low in air and better in water. Published compressed air tests reached about 6 to 14% efficiency.

### Charged wall for water

For water only. Narrow channels with charged walls drag ions along and create a voltage, called a streaming potential. Evaporation can drive the flow through the channels.

Risk: output per channel is tiny. A useful device needs many channels in parallel, and the pressure drop across them is the energy cost.

## Working fluids and drivers

The duct captures a flow. It does not create one. Each test must name its driver.

- Thermal draft: air heated below the duct rises through it. Draft speed grows with duct height and with the temperature gap. A 10 m stack with air 10 °C above ambient gives about 2.6 m/s before any extraction load.
- Wind: the mouth faces the wind, or sits where a building edge speeds the wind up.
- Water current: a river, a tide, or a pipe flow. Water at 1 m/s carries about 500 W per square metre of capture area, against 16 W for air at 3 m/s.

## What gets measured

- Net electrical power out. Any power used to drive or prime the flow is subtracted.
- Power per square metre of mouth area. Power per square metre of total device area, reported separately.
- Pressure drop across the duct, with the wall active and with the wall locked still. The gap between the two is the extraction cost in flow terms.
- Flow speed at the mouth and in the narrow section.
- The speed band where the device produces, and the band where it stops.

## Prototype ladder

### P0: paper model

Model one candidate settlement. Predict net power, pressure drop, and the working speed band for a named driver. No building at this step.

Kill rule: the ladder stops if the modelled net power under the named driver is under 0.1 W per square metre of mouth area.

### P1: bench duct, air

A bench duct with one active wall section, run in a wind tunnel or in front of a calibrated fan. Compare wall active against wall locked, at the same fan setting.

Kill rule: the design dies if locking the wall changes output by less than measurement error, or if the pressure drop with the wall active cuts flow through the duct by more than half.

### P2: bench duct, water

The winning air design, or the charged wall design, run in a water channel at 0.5 to 1 m/s.

Kill rule: the design dies if net power per mouth area in water does not beat the air result by at least ten times, since the fluid itself offers about thirty times the power at those speeds.

### P3: outdoor draft test

The surviving design on a heated stack outdoors, run for full days. Report energy per day, not peak power.

## Open questions

- Which settlement of the central conflict keeps the widest working speed band?
- Can an active wall section be tuned in place, by changing its stiffness or mount damping, as flow speed changes?
- Does an eddy formed by the wall carry energy to an inner extractor with less loss than direct wall extraction?
- In water, can charged wall channels and a moving wall work in one duct without the channels clogging the flow path?

## Relation to the parent project

thermal-capture holds the wider question, the full founding record, and the other routes: direct thermal excitation, capture against the night sky, capture against stored past temperature, and charged walls in open water.

This project takes one route only: flow capture in a duct where the wall does both jobs.
