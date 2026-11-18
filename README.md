# The Wildlife Archives — Version 10 (52 selected collections)

This update adds the official Marwell Zoo animal directory snapshot (81 entries), provides direct official inventory links for Chester, Marwell and Whipsnade, and includes a 52-collection coverage audit. Existing starter data from V9 remains. **This is not a complete 52-zoo species database.** See `collection_coverage.csv` for missing and partial collections.

Data sources: https://www.marwell.org.uk/animals/ (checked 2026-11-18); https://www.chesterzoo.org/footer/corporate-information/animal-inventory ; https://www.whipsnadezoo.org/whats-here/animals .

To update: export your app backup first; replace GitHub Pages files; commit; close and reopen the installed app. Your existing visits and photos are kept in the device's IndexedDB, not in GitHub. For previously customised collections, use **Merge published species updates** to add new starter names without overwriting personal additions.


V11: Additional sourced published entries for Belfast Zoo, Folly Farm, Hemsley Conservation Centre and Blackpool Zoo. These are partial and are not certified complete. Existing customised checklists can use Merge published species updates. Source records: official_additions_2026.csv.

V12: Added official public animal-directory species for Drusillas Park and Peak Wildlife Park. Source records in official_additions_v12.csv. These lists are partial, not complete stock inventories.

V13: Added Wildwood Trust Kent official animal directory (52 entries) and New Forest Wildlife Park official animal directory and interactive map (35 entries). These are not guaranteed complete stock inventories. Wildwood Trust entry refers to the Kent collection, not Devon. Ural Owl is marked offshow by the source. Source records in official_additions_v13.csv.

V14: 29 The Deep species entries from official habitat pages and 2026 shark article. Species and exact URLs in official_additions_v14.csv. Partial inventory; other collections still need research.

V15: Added 70 sourced animal-page entries for Crocodiles of the World and Wildheart Animal Sanctuary. See official_additions_v15.csv. Partial, not exhaustive.

V16: Added official animal-directory entries for Wingham Wildlife Park, Yorkshire Wildlife Park and Africa Alive. Source rows: official_additions_v16.csv. Not exhaustive.


## V17 additions
Added official-page species entries for Knowsley Safari and Longleat. Public directories are not complete stock inventories. Source-by-species provenance: official_additions_v17.csv. Existing IndexedDB visit and photo records are not deleted by the code update; export a backup before deployment.


Version 19: Added 181 sourced checklist entries for Port Lympne, Howletts, and Colchester. These are NOT full inventories. Sources in official_additions_v19.csv. Existing IndexedDB records are not deleted by this update.


Version 20: verified official 2026 park maps for Howletts and Port Lympne; 10 newly recorded map-labelled species. Existing 52-collection lists remain incomplete. No historical visit or photo data are intentionally deleted; export an app backup before updating.


## Version 21 additions
Dartmoor Zoo official animals directory (42 names) and The Big Cat Sanctuary official cats directory plus 2025 map (16 cat taxa/varieties). This is a published-name checklist, not a complete stock census. Historic/unverified records are separately recorded in historical_holdings_v21.csv. Personal visits/photos remain in device IndexedDB and are not included in this ZIP; export a backup before updating.


## Version 22
Added 28 Paignton Zoo **map exhibit labels** transcribed from the official January 2026 map. These are NOT all species-level identifications (e.g. tigers, wallabies, pelicans) and do NOT establish a complete inventory. Source and status in official_map_additions_v22.csv. Existing IndexedDB collections, visits and photos are not deleted by the app update; back up before deployment.


## Version 23 Paignton Zoo verification
Added 26 distinct names from official pages, bringing Paignton starter list to 54 entries. This is NOT a complete 190-species inventory. The 2026 map contains generic labels and these remain in the starter list. Source file: paignton_official_expansion_v23.csv. Back up local app data before replacing files; existing IndexedDB visits and photos are not changed by the ZIP.


Version 24: Chester 2025 official bird and fish inventory additions. Stocklist may include off-show animals and may differ from current 2026 holdings. Additional entries are merged into built-in Chester checklist; user-customized lists can use Merge published species updates.

Version 25: Added 26 Marwell inventory entries (18 invertebrates, 8 fish) from published 2025 stocklist. Some may overlap existing names. Not a complete stocklist transcription.


V26: Added 136 sourced Whipsnade January 2025 inventory entries (partial transcription); current holdings and on-show status are not guaranteed. See whipsnade_2025_inventory_v26.csv.


V27: populated 23 previously blank collections in alphabetical order with source-tracked starter animal lists. These are NOT complete inventories. Birmingham SEA LIFE Centre and National SEA LIFE Centre are aliases of the same venue, but retained as requested. Use Merge published species updates for previously customized collections. See previously_empty_collections_v27.csv.


Version 28: fixed exact zoo key matching (previous audits miscounted Chester and aliases); fixed custom collection views to union saved and published entries, without overwriting saved visit records; expanded Bristol Zoo Project from its January 2026 official map and Cotswold Wildlife Park from its four official animal directories. Note: map generic animal labels and public directories do not constitute full inventory. Coverage audit v28 uses the same matching logic as the app.


Version 29: Edinburgh Zoo's publicly listed animal directory reviewed and added; see edinburgh_official_directory_v29.csv. The coverage_v29 file explicitly flags that NONE of the 52 collections has been verified against a complete current inventory. Do not treat checklist counts as species totals.


Version 30: additional official 2026 Longleat animals, including newly arrived maned wolves and lechwe. Counts are checklist entries, not verified current species totals. None of 52 collections is certified complete. See coverage_audit_v30.csv.


V31: reviewed seven under-30 collections against official animal pages, including a full official online directory for Highland Wildlife Park and official breeding programme list for Folly Farm. The Big Cat Sanctuary is a ~14 species collection and should not be artificially padded to 30. See coverage_audit_v31.csv for still underfilled collections. No complete-current-inventory verification is claimed.

Dudley Zoo: official 12-page online animal directory added (102 directory labels); see dudley_official_directory_v31.csv. Directory listings are not a guaranteed full live stocklist.


Version 32: Howletts and Hemsley official 2026 directory reconciliation, plus historical Howletts map and 2025 husbandry evidence. Port Lympne official featured animals checked. Added source-specific CSV. Species present in historical sources are not necessarily currently on show; no collection is certified complete.


Version 33: Newquay Zoo expansion, with 2026 official highlights and species-level identifications from a 2024 official visitor map. Older map holdings must not be interpreted as verified present in November 2026. The official zoo history site's November 2025 Species360 summary reported 126 species, including 51 birds, 40 mammals, 18 reptiles, 9 amphibians and 8 invertebrates; the app's list is still incomplete. See newquay_source_review_v33.csv.

## Version 34
Removed Birmingham SEA LIFE Centre and Birmingham Wildlife Conservation Park from the 50-item built-in directory. Existing local visit data for removed venues is preserved, but those collections are hidden from the main collection browser. Reviewed and expanded 15 requested zoos against their published animal pages or maps, with source audit CSV. **Not a complete live species inventory.** Several zoo sources provide only representative animals, and some additions are generic display labels; do not mistake checklist totals for verified species counts. In particular, Birdworld officially reports 181 species, Woburn over 80, Lincoln 70, Jimmy's Farm over 100 species and breeds, and Longleat over 120. Additional reconciliation is needed before claiming exhaustive accuracy.

## Version 35
Removed Lake District Wildlife Park, Lakeland Wildlife Oasis, Lakes Aquarium, and Lincoln Zoo from the built-in collection directory (46 remain). Existing saved visits/sightings are not deleted; retired venues are hidden from collection browse. Export a backup before replacing your deployed files.

## Version 36
Added independently sourced entries for Birdworld, Welsh Mountain Zoo, West Midlands Safari Park, Woburn Safari Park, Longleat and SEA LIFE Weymouth, using official zoo animal directories, visitor maps and conservation pages. Includes official_species_review_v36.csv and coverage_audit_v36.csv. Retains the 46 selected collections. The app is usable as a personal tracker but **NOT an exhaustive, verified 2026 stocklist**; some prior entries and newly sourced map/conservation entries may be historical, broad labels or taxonomic aliases.

## Version 37 — permanent checklist removal fix
Fixed published animals reappearing after removal. Per-collection `excludedSpecies` tombstones persist in IndexedDB and are applied when merging built-in published species. Adding a removed species explicitly restores it. Existing sightings and photos are not deleted. Backup export/import should preserve exclusions because the whole collections store is included. Replacing a shared checklist now excludes unselected published entries. Existing user data is migrated lazily without database schema changes.

## Version 38
Port Lympne Reserve: removes generic Tiger and Sumatran tiger from built-in checklist and suppresses them even in saved local checklist overrides, without deleting sighting/photo data. Adds Amur tiger, Amur leopard and banded mongoose (last two user-reported, not independently verified on current official species directory). Retains lesser and greater bamboo lemurs, both listed on official Port Lympne website. Adds zoo-site species at Welsh Mountain Zoo and SEA LIFE Weymouth, and map-labelled animals at Howletts (map dated July 2024). 46 collections retained. See species_corrections_v38.csv for evidence and limitations. Exports of old sightings remain intact. Existing user-managed exclusions remain respected.
