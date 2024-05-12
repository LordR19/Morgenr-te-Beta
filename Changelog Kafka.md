Changelog for 2.1.4 "Kafka"

General:
- Included the "Rise of the Publishing Industry" Mod (PBI) by Kaznoku. Added and enhanced PBI events and JEs.

Characters:
- Franz Kafka (random Austrian Writer)
- Robert Musil (random Austrian Writer)
- Zweig Stefan (random Austrian Writer)
- Hans Christian Andersen (Danish Writer)
- Honoré de Balzac (French Writer)
- Alexandre Dumas (random French Writer)
- Jules Verne (random French Writer)
- J.R.R Tolkien (randim British Writer)
- H.G. Wells (random British Writer)
- Bram Stocker (random Irish Writer)
- Henrik Wergeland (Norwegian Writer)
- Selma Lagerlöf (random Swedish Writer)
- August Strindberg (random Swedish Writer)
- Gottfried Keller (random Swiss Writer)
- Jeremias Gotthelf (possible starting writer for Switzerland)
- Johanna Spyri (random Swiss Writer)
- Rodolphe Töpffer (possible starting writer for Switzerland)
- Edgar Allen Poe (American Writer)
- Ryūzō Torii (Japanese Archaeologist/Anthropologist)
- 1 Easter Egg Character

Archaeology:
- Added four new technologies: Egyptology, Assyriology, Aegean Archaeology, Pre-Columbian Archaeology.
- One of these techs can be chosen via JE to specialize a nation in one archaeological field.
- Techs can also be gained via archaeological milestones like Decipherment of Accadian gives Assyriology, Discovery of Machu Picchu Pre-Columbian Archaeology etc.
- Special technology gives +1 yearly artifacts for each excavation in the corresponding archaeological site.
- Double the chance of finding a Major Artifact during excavations if you have the corresponding Archeology Tech (e. g. double chance to find Nefertiti if you have Egyptology).
- Added four new character traits for archaeologists: Egyptologist, Assyriologist, Aegean Archaoelogist, Pre-Columbian Archaeologist.
- Traits can be gained by doing expeditions in a certain archaeological region. After doing two expeditions to Egypt, there is a 50% chance that an archaeologist gets the Egyptologist trait. After three expeditions, he will get it automatically. This is true for every region/trait.
- New Archaeologists start with the corresponding trait, if they have one of the specialized technologies. E. g., a country with Egyptology will always generate new archaeologists with the egyptologist trait.
- Archaeologists can have several specialization traits.
- Archaeologists with a specialized trait will get +5 artifacts at the end of an expedition in the corresponding archaeological site, e. g. doing an expedition as an Assyriologist in Babylonia or Assyria.
- Archaeologist with a specialized trait will get +1 clue when inspecting an excavation site in the corresponding archaeological site.
- Modern Archaeology tech gives +1 yearly artifact for each excavation.
- Modern Archaeology no longer gives a prestige bonus.
- Changed artifacts at the end of an expedition: you should get some more artifacts than before.
- Added Vilcabamba as a possible archaeological discovery in Peru.
- Added Nazca Lines as a new JE.

Compatability:
- Removed the mr_starting_inventions.txt file which should improve compatability with various mods.
- Various changes to improve compatibility with mods that set up another scenario.
- Added built in compatibility for most of Basileia Romaion (still needs a Compatch).

Pacific Expeditions:
- Made Oceanic Domination Modifier a bit stronger (10 % more prestige from navy power, 10 % more navy defense, -10 % convoy recquirements), also added large navy tech add when JE is completed

Music:
- The Mozart Monument Event now tells you when the monument will be finished.

Paleontology:
- Paleontology tech does no longer need Early Archaeology.
- Paleontologists can only be promoted with Paleontology Tech.

Anthropology:
- New Anthropology Tech. All recquirements which mentioned Modern Archaeology will now need Anthropology instead.
- Anthropologists can only be promoted with Anthropology Tech.

Natural History:
- New Nature Protection Tech.
- Moved Nature Reserve from Genetics to Nature Protection.
- Added historical volcanos to all states where volcanic eruptions took place between 1836-1936.
- Volcanic eruptions will only occur in states with volcanoes (instead of "regions" in vanilla).

Astronomy:
- Astrophysics no longer gives a prestige bonus.
- Changed Astrophysics and Modern Physics JE to Astrophysics only.
- The observatory now has workers again due to problems with input resources and output bonuses.
- Complete redesign of the observatory for the future in the areas of astronomy, physics, chemistry, meteorology and geomagnetism.
- The Astrolab is now the final stage of the Observatory's astronomy division rather than its own production methods group.
- (Almost) All PMs in the Observatory now cost goods.
- Annual astronomical objects are now no longer calculated based on technology alone, but also whether the associated Astronomy PMs are switched on. For example, an active Modern Telescope now gives +5 Astronomical Objects per year, instead of just researching Modern Astronomy.

Meteorology:
- Instead of flat tech bonuses, Meterology in the Observatory will give bonuses to agrarian buildings and a small military tech bonus.
- Added Modern Weather Station in Observatory as new PM. This will use rubber (instead of the weather station).

Chemistry:
- Added a Chemistry Lab PMG in the Observatory. This is still WIP and will be expanded later.

Physics:
- Added Modern Physics Tech. In contrast to Astrophysics, this can be researched after Electromagnetism.
- Seperated Astrophysics and Modern Physics in many events were they were handled as one technology.
- Added Nuclear Physics Tech. Be careful with that stuff.
- Added new good: Uranium.
- Added new building: Uranium mine.
- Uranium glassware (PM) for Glass industry
- Added new Production Method Group in the Observatory: Institute for Physics. This will give Production Tech Bonus (but will need uranium for the more advanced tiers).

Aviation
- Pilots no longer are generals. They behave like other Morgenröte Characters as Void-Character. Generals may get the Pilot trait, however.
- Added experience bar to pilot
- Pilots should show up more frequently now (outside the Schneider Trophy event, which gives you a free pilot).
- Added Variables to pilots like Number of Records, Number of Schneider Trophy Races/Victories. This is still WIP.
- Manfred von Richthofen will be created randomly for a German Nation instead by event.

Engineers:
- If you get a new engineer you can change their specialization even if the 5 years didn't pass yet.

Bugfixes:
- Historical Science Focuses are now properly removed, if you change the rule.
- Research Projects do no longer think you are an AI and get removed just because there is another project to do.
- New Engineers no longer work on imaginary projects.

Performance:
- Various small changes to massively improve performance with the mod.
- Removed Nationalization of various cultures to improve performance and compatibility.
