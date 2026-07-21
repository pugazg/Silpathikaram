# Material Culture Bible — Part 3

## Scope

This part governs fire-sequence objects, military logistics, the Pattini stone and shrine, the object-continuity register and department sign-off.

## 11. Fire-sequence objects

### Source control

- **Anchors:** HWT-0131–HWT-0144
- **Status:** `LOCKED_SOURCE` for selective-fire logic; `DEVELOPMENT` for production execution.

### Requirements

- city-zone continuity map;
- protected-category identifiers based on action and space, not modern labels;
- household, market, sacred and court objects established before fire;
- evacuation loads and routes;
- fire-safe breakaway architecture;
- ash, damage and survival continuity;
- protected spaces that remain legible without appearing untouched by fear or displacement.

### Caution

- Do not use random destruction inserts.
- Every damaged object should belong to an established household, institution or work system.
- Selective fire must not become visually painless or morally simple.

## 12. Military and expedition material system

### Source control

- **Anchors:** HWT-0170–HWT-0188
- **Status:** `LOCKED_SOURCE` for systems and sequence; `HISTORICAL_RESEARCH` for exact forms.

### Requirements

- provisioning vessels and grain stores;
- cooking lines and water supply;
- written records and tribute documentation;
- standards, drums and horns;
- infantry equipment;
- cavalry and elephant tack;
- chariots;
- command and medical areas;
- camp shelters and sanitation;
- Ganges-crossing fleet;
- captive handling and stone-transport systems.

### Continuity rule

Weapons, armour, tack and wounds must carry forward from mobilisation through battle, Ganges ceremony and the return to Vañci.

### Caution

War must appear as administration, labour, animal management and bodily cost—not only battlefield spectacle.

## 13. Pattini stone and shrine system

### Object life cycle

1. stone-source debate;
2. Himalayan extraction;
3. transport and captive-king victory display;
4. Ganges consecration;
5. southward return;
6. specialist carving and shrine construction;
7. installation;
8. recurring offerings and maintenance.

### Source control

- **Anchors:** HWT-0168–HWT-0169, HWT-0182–HWT-0185, HWT-0193–HWT-0194
- **Status:** `LOCKED_SOURCE` for sequence; `HISTORICAL_RESEARCH` for technology and form.

### Production versions

- quarry or extraction stone;
- transport stone;
- consecration stone;
- carving-stage forms;
- installation form;
- completed hero image;
- maintenance and offering duplicates.

### Requirements

- visible weight and transport difficulty;
- measurement and dressing marks;
- specialist tools;
- water and consecration continuity;
- safe rigging and performer interaction;
- documented transition between stone stages;
- recurring flower, boundary and lamp systems after installation.

### Caution

The image and shrine cannot appear complete through royal intention alone. Labour, tools, specialists, ritual negotiation and time must remain visible.

## 14. Object continuity register

Every recurring hero object should receive:

- stable prop ID;
- source IDs;
- first and last scene IDs;
- ownership history;
- condition history;
- duplicate count;
- stunt or VFX versions;
- storage and handling restrictions;
- sound identity;
- unresolved historical questions.

### Priority register

1. Kaṇṇaki anklet pair and surviving anklet;
2. queen’s anklet reference set;
3. Mādhavi’s yāḻ;
4. flower-letter;
5. Pāṇḍya sceptre, parasol and gate bell;
6. Cēra sword, parasol and proclamation drum;
7. Pattini stone stages and installed image;
8. ritual drums, horns and bells by community;
9. Kōvalaṉ and Kaṇṇaki travel loads;
10. Mādhari household dairy objects;
11. military standards and command documents;
12. veteran weapons and wound-linked equipment.

## 15. Condition-state model

Each hero object should use explicit condition states such as:

- `NEW_OR_CEREMONIAL`;
- `HOUSEHOLD_USE`;
- `TRAVEL_WORN`;
- `CUSTODY_OR_TRANSACTION`;
- `DAMAGED_OR_BROKEN`;
- `CONSECRATED`;
- `INSTALLED_AND_MAINTAINED`.

Changes between states must cite the scene that causes them.

## 16. Department sign-off rule

No hero object is production-locked until the following fields are agreed:

- source fidelity;
- historical reconstruction status;
- visual interpretation;
- performer usability;
- scene continuity;
- sound requirement;
- safety requirement;
- cultural and religious review;
- documented invention.

## 17. Required machine register

A future CSV should contain:

`prop_id,prop_name,source_ids,first_scene,last_scene,owner_history,condition_states,department,status,research_questions`

The register should be populated only after prop IDs and scene ownership transitions are reviewed against all 102 scene units.
