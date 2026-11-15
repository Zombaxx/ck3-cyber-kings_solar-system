# Cyber Kings: Solar System - Localization Experimental (submod)

Localization ideas that change the feel of vanilla text more than the main mod should without the modder's sign-off. Enable it after the main mod in the launcher (`mod/ck3-cyber-kings_loc-experimental.mod`). Everything here is text only, except the space-lane travel events (small gold, prestige, piety, stress and delay effects). Move a file into the main mod once it is approved.

| File | What | Status |
|---|---|---|
| `localization/replace/english/cyber_exp_eras_l_english.yml` | Culture eras renamed: Tribal → Age of Ruin, Early Medieval → Age of Recovery, High Medieval → Age of Reclamation, Late Medieval → Age of Ascendancy; descriptions mention the Collapse and the space lanes | proposal, 2026-11-12 |
| `events/ck_exp_lane_events.txt`, `common/on_action/ck_exp_lane_on_actions.txt`, `localization/english/ck_exp_lane_events_l_english.yml` | Four flavor events while a player ruler (count or above) travels a space lane (`ck_space_lanes` region): Aurora Storm, The Guild's Toll, Derelict in the Lane, The Mare Incognitum. 20% chance per lane province entered, at most one per year, each event at most once per 5 years. Hooked by appending `on_actions` to vanilla `on_travel_plan_movement` (no vanilla file overridden). | proposal, 2026-11-13; not yet seen in game |

Rejected or parked ideas are in `_dev/LOCALIZATION_SOLAR.md` §6.
