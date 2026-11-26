# Mysthaven task design reference

Detailed walkthroughs, feedback and recovery behavior, and HCI notes for the 25 tasks indexed in Appendix A of the Mysthaven report. The report contains the corresponding screenshots.

## 02 Restore the Crest

**Room:** Grand Hall

Use the restored crest as a reference and drag all four fragments into their matching gaps.

**Feedback and recovery:** Open gaps brighten during dragging. A correct piece locks with a gold flash; a wrong gap flashes and the fragment returns. The footer shows pieces placed, and Reset removes them.

**HCI links:** Direct manipulation: players move the actual puzzle pieces. Match with the real world: fitting broken pieces resembles restoring an object. Recognition rather than recall: the finished reference and piece shapes remain visible. Constraints and recovery: a piece cannot lock into an incorrect gap.

## 06 Restore Torn Record

**Room:** Archives

Rotate and fit all eight fragments using the restored document as a guide, then press Complete Record.

**Feedback and recovery:** A matching tear highlights differently depending on whether the fragment still needs rotation. Incorrect placements return to the tray with a hint. Only a correctly positioned and oriented fragment locks.

**HCI links:** Match with the real world: torn edges and page orientation resemble a physical jigsaw. Direct manipulation: fragments are moved and rotated as visible objects. Recognition: the restored reference supports comparison. Constraints and error recovery: invalid pieces remain available for correction rather than damaging the reconstruction.

## 07 Set the Table

**Room:** Dining Hall

Place one of each requested item at all six seats, then press Complete.

**Feedback and recovery:** Correct items stay at their places and progress advances. An unsuitable item or wrong position returns the item to the tray with a hint.

**HCI links:** Match with the real world: arranging tableware at seats uses a familiar dining activity. Direct manipulation: players place visible utensils and dishes. Recognition: tonight’s requirement stays available. Constraints: unsuitable items cannot satisfy the task. The visible requirement carries the interface memory burden while the player performs the placements.

## 08 Inspect Serving Ledger

**Room:** Dining Hall

Multiply tables by servings for each course. Adjust the wrong total with −/+ and press Balance.

**Feedback and recovery:** Edited totals change appearance. An incorrect Balance shakes the ledger; correct totals earn a seal and Ledger Balanced. Reset restores the ledger as originally found.

**HCI links:** Match with the real world: rows and totals resemble a bookkeeping ledger. Recognition: operands and recorded totals remain together for comparison. Feedback distinguishes amended entries and successful balancing. User control permits adjustment and reset. The calculation is the game challenge; the controls mainly instruct the system through value changes.

## 10 Check Pantry List

**Room:** Kitchen

Select the three jars on the pantry list and press Check.

**Feedback and recovery:** Incorrect jars are named, shake and return to the shelf, while correct selections stay picked. A successful check ticks the list and shows Pantry Checked before completion.

**HCI links:** Match with the real world: a pantry checklist is a familiar stock-checking activity. Recognition rather than recall: the list remains beside the jars. Error recovery: feedback identifies which selections to change without discarding correct ones. Feedback and closure: the ticked list confirms that checking is finished.

## 11 Stop the Stove Flare

**Room:** Kitchen

Press Stop Heat when the marker enters the striped zone. Repeat as the zone shifts and narrows.

**Feedback and recovery:** A safe hit produces steam and reduces the flames. A miss increases Heat, flares the fire and says Too Early or Too Late. Three misses overheat the stove; Retry or Reset starts another attempt.

**HCI links:** Match with the real world: a heat gauge and rising flames communicate overheating. Visibility: separate Safe Hits and Heat counters show progress and risk. Diagnostic feedback explains timing errors. Playability: increasing speed creates challenge. This is a timing-button task, not a drag-and-drop interaction.

## 13 Collect Moon Herbs

**Room:** Courtyard Garden

Match the names and pictures on the request cards to four plants and tap each match.

**Feedback and recovery:** A selected correct herb becomes a harvested stub, sends light toward its request card and gains a check. Collected advances toward 4/4. A wrong herb shakes with a cross and message; no penalty is applied.

**HCI links:** Match with the real world: finding and collecting plants uses a harvesting metaphor. Recognition: pictures and names support comparison with visible requests. Direct object selection links a tap to the harvested plant. Redundant feedback: checks, crosses, text and scene changes provide information beyond color alone.

## 14 Examine Fountain

**Room:** Courtyard Garden

Rotate the pipes to create one continuous water route with no open joints.

**Feedback and recovery:** Water flows live, and amber dots identify open joints. The drain changes to Flowing when the route is complete. There is no hard failure; keep rotating or Reset to the starting layout.

**HCI links:** Match with the real world: joined pipes carry water from inlet to drain. Direct manipulation: players turn the pipe objects themselves. Continuous feedback exposes the effect of each turn. Error recovery remains reversible, and visible open-joint markers reduce blind trial and error.

## 15 Check Stair Lock

**Room:** Courtyard Garden

Tap stones to toggle them and their neighbors until the whole grid is lit.

**Feedback and recovery:** Stones visibly change as they flip. After ten presses a tip explains that each stone only needs one press, in any order. The stair arch lights when solved; Reset restores the initial pattern.

**HCI links:** Immediate feedback shows both the chosen stone and its linked effects. Consistency makes the neighbor rule predictable. Contextual help supports recovery when players struggle. The linked toggling is an invented puzzle rule, so the real-world link is the lock’s setting, not a claim that physical locks behave this way.

## 16 Synchronize the Clock

**Room:** Clock Tower

Drag the hands or use −/+ to match the target time, then press Lock.

**Feedback and recovery:** Hands move and tick as they change. A wrong Lock shakes the clock and identifies the wrong hand or hands. A correct setting glows and chimes before completion.

**HCI links:** Match with the real world: an analog dial and hands use familiar time conventions. Direct manipulation and natural mapping: rotating a hand changes its indicated time. Recognition: the target remains visible. Flexibility: buttons provide an alternative to dragging; specific error messages guide correction.

## 17 Replace the Gear

**Room:** Clock Tower

Match a gear to the slot’s shape and dimensions. Drag it into place and press Test Rotation.

**Feedback and recovery:** A gear appears at its own size, exposing a gap or overlap if wrong. A failed test jams, explains Too Small or Too Large and returns it. Correct gears turn together and complete the task.

**HCI links:** Match with the real world: the replacement must fit a mechanism. Direct manipulation: the actual gear moves into its slot. Recognition: visible size, teeth and measurements support comparison. Diagnostic feedback explains the mismatch, and reversible placement permits correction before another test.

## 18 Reconnect CCTV

**Room:** Security

Drag each camera plug to the socket with the matching symbol and color.

**Feedback and recovery:** Correct plugs lock, their monitors change to Online and the count increases. Wrong sockets flash, buzz and return the cable with an explanation. Reset disconnects every cable.

**HCI links:** Match with the real world: reconnecting cables represents restoring equipment. Direct manipulation: the cable follows the player’s drag. Mapping: identical symbols link source and destination. Accessibility: symbols accompany color. System status: each live monitor shows the result of its own successful connection.

## 19 Review Camera Footage

**Room:** Security

Scrub through the feeds, choose the anomaly type and press Flag Feed while the evidence is visible.

**Feedback and recovery:** Wrong flags distinguish an empty feed, unrelated event, wrong type or wrong time; a short cooldown allows retry. A correct flag circles the evidence and completes the task.

**HCI links:** Match with the real world: camera feeds and playback controls resemble a recording viewer. Direct manipulation applies to the timeline scrubber. Recognition: the report and feed labels provide context. Diagnostic feedback explains why the evidence is insufficient; player control supports replay and inspection.

## 20 Analyze the Sample

**Room:** Research Lab

Insert the capsule and hold the frequency within 64 ± 8 for two seconds. At 100%, press Confirm Signature.

**Feedback and recovery:** Live and target traces become aligned; calibration progress and status labels update. Releasing pauses calibration. Outside the band the scanner reports Misaligned. Confirmation stays disabled until calibration is complete.

**HCI links:** Match with the real world: sample insertion and instrument calibration use a laboratory metaphor. Direct manipulation: capsule and slider are moved visibly. Error prevention: stages and confirmation unlock only when ready. Feedback and recognition: traces, band and percentage reveal the required adjustment without memorized settings.

## 21 Mix the Formula

**Room:** Research Lab

Add each ingredient in the order and quantity on the formula card, then press Mix Solution.

**Feedback and recovery:** Added ingredients animate into the cauldron and receive ticks. An incorrect ingredient or amount produces an explanatory message while preserving earlier correct additions. Cancel exits the measuring choice; Reset starts over.

**HCI links:** Match with the real world: measuring against a recipe makes the fictional mixture understandable. Recognition: order and units stay visible. Error recovery preserves completed work. Constraints prevent mixing before all four additions. Interaction is mainly selection and amount entry, rather than direct dragging.

## 22 Scan Vitals

**Room:** Infirmary

Hold the scan button and steer the indicator into the center band until progress reaches 100%.

**Feedback and recovery:** Stable, Unstable and Paused states explain whether scanning advances. Leaving the band pauses progress and gives steering guidance; releasing also pauses while preserving progress. Reset returns the scan to zero.

**HCI links:** Match with the real world: the body image, beam and monitor establish a scanning metaphor, not a clinical simulation. Natural mapping links left/right steering to indicator movement. Visibility: beam position and percentage show progress. Flexibility and recovery: alternative controls and resumable scanning reduce unnecessary frustration.

## 23 Collect Supplies

**Room:** Infirmary

Add up what both beds need, dispense those quantities and press Pack Tray. Tap a tray compartment to return extras.

**Feedback and recovery:** The packed total shows progress without revealing every correct compartment. A wrong check shakes the incorrect compartments. Reset empties the tray; the correct quantities produce the completion banner.

**HCI links:** Match with the real world: reading a requisition and dispensing supplies resembles stock preparation. Recognition: both bed requests stay visible. Natural mapping: one tap adds or returns one item. Error recovery permits local corrections. The addition is the intended puzzle; the interface retains the request rather than demanding it from memory.

## 24 Reaction Drill

**Room:** Training Hall

Press Start Drill and click each raised target’s bullseye before it drops.

**Feedback and recovery:** A hit contributes to the displayed score; a missed target sinks without a point. Fewer than eight hits after all ten targets produces a failed attempt with Retry.

**HCI links:** Match with the real world: a training hall and bullseyes communicate target practice. Direct target selection: players point at the object they intend to hit. Feedback shows performance. Playability: time pressure creates deliberate challenge. Fitts’ law is relevant to target size and distance, but no measured pointing-time model is claimed.

## 25 Inspect Rack

**Room:** Training Hall

Match all three items to their chalk outlines by dragging or by selecting an item and tapping its destination.

**Feedback and recovery:** A wrong outline shakes and leaves the weapon available to try elsewhere. A correct placement locks and glows, gaining a tick. Rack in Order confirms success; Reset removes all weapons.

**HCI links:** Match with the real world: returning equipment to a storage rack is familiar. Direct manipulation: the weapon moves into position. Recognition through shape: outlines provide visible matching cues. Flexibility: tap-and-tap avoids mandatory dragging. Constraint feedback prevents an incorrect placement from silently counting.

## 26 Repair Wiring

**Room:** Maintenance

Drag each of the four plugs to the terminal of the same color.

**Feedback and recovery:** A correct cable snaps in with a click, flash, illuminated lamp and increased count. A wrong terminal sparks and buzzes, returning the plug. Completed connections remain in place.

**HCI links:** Match with the real world: wires and terminals suggest circuit repair. Direct manipulation: the plug follows the pointer. Feedback and reversible errors make the effect understandable. Accessibility limitation: this task document describes color matching; it does not establish the independent shape coding documented for CCTV, so color-independent completion needs checking.

## 28 Balance the Supply Lift

**Room:** Storage

Place the 25 kg and 15 kg crates on one side and both 20 kg crates on the other. Press Test Lift.

**Feedback and recovery:** Weight totals, gauge and platform tilt respond immediately. Tests explain missing crates, imbalance or overload without discarding the arrangement. Correct loading levels and raises the lift.

**HCI links:** Match with the real world and natural mapping: the heavier platform moves down. Direct manipulation: crates are moved between physical-looking locations. Visibility and recognition: totals and printed weights remain available. Reversible actions and specific test messages support trial, diagnosis and correction.

## 29 Find Inventory

**Room:** Storage

Open two crates at a time and match their stamps until all four pairs are found.

**Feedback and recovery:** Crates react when opened. Different stamps flash and close again, while matching pairs glow and remain visible. Manifest Complete ends the task; Reset closes every crate.

**HCI links:** The crate and manifest setting matches the Storage context. Feedback and visible progress distinguish temporary reveals from completed pairs. Consistency gives every crate the same opening behavior. Recall of hidden positions is intentional gameplay here; the visible manifest supports recognition of collected stamp types but does not remove the memory challenge.

## 30 Restore Passage Lights

**Room:** Underground Passage

Rotate the tiles to route power from the generator to the lamps. Use Test Circuit to check for unpowered lamps and open ends.

**Feedback and recovery:** Powered paths glow and lamps light immediately. A cracked connection sparks and temporarily switches the network off, then it retraces the revised circuit. All five lamps lit without overload complete the task.

**HCI links:** Direct manipulation: players rotate the visible route pieces. Mapping and feedback: energy follows the connections actually formed. Error diagnosis: Test Circuit exposes leaks. The pipe-style power network is a simplified game metaphor, rather than a literal electrical model; its readable behavior makes experimentation possible.

## 31 Check Valve

**Room:** Underground Passage

Press Start, then use Pump and Bleed to keep the gauge in the stable range until the interval ends.

**Feedback and recovery:** A safe-band highlight, needle, pressure readout and stable-second lamps show the state. Leaving the band restarts the interval and warns the player. Reset starts the line again; Pressure Stable confirms success.

**HCI links:** Match with the real world: pumping and releasing steam map to increasing and decreasing pressure. Natural mapping makes the two controls distinct. Continuous feedback supports adjustment, while the visible stable-time count explains why completion has or has not occurred. Recovery permits further correction instead of a permanent failure.

## 33 Inspect Boundary Seal

**Room:** Veil Chamber

Start at the glowing gem, follow all five links in either direction and return to the starting gem.

**Feedback and recovery:** A line follows the drag and each gem plays a rising note. Leaving the path breaks the link and requires restarting at the glowing gem. A closed circuit produces The Seal Holds.

**HCI links:** Direct manipulation: the player traces the actual visible path. Recognition: the glowing start and drawn links indicate where to go. Immediate visual and auditory feedback confirms contact. Flexibility: tapping alternatives reduce reliance on precise dragging. The sigil is a fantasy metaphor; the interaction uses familiar path-tracing behavior.
