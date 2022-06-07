--- PREMISE ---
- The guide won't cover (for now) issues that need to be fixed on cars/tracks (fuel cons, trajectories...)
	

--- EXPLOITING SYNTAX ---
- Each parseable instruction is valid. Some do break the game, others can be exploited. This is a collection of what the ACICP staff found
- AI description in opponents.ini vs eventx.ini
	- points assignment persistency
	- making guest racers by reducing car number in events, changing names each time
	- changing ai levels for different races
- Ballasts and air restrictors do not work
- Track conditions must be specified with presets
	- If an invalid number is entered (or the single line of code is deleted), by default the UI says "fast", and race.ini is compiled so that basically you start with an optimum track
	- At the current moment no way to put new presets has been found
- Custom single event objectives

--- AI ---

- AI always runs w/tyre blankets
- AI is affected by track conditions, but you may want to lower it, say, if you want to make rookie drivers scared of rain

--- GOOD ADVICE ---
- Desired workflow: ideation, quick drive presets, testing, implementation, user testing, deployement
- https://github.com/archibaldmilton/Girellu/wiki/List-of-Assetto-Mods
- https://www.reddit.com/r/assettocorsa/comments/o9ogjy/how_to_improve_ai_pit_strategy_diversity_by/
- Setting AI 
	- distribution (linear, logarithmic)
	- I guess from an arcade pov the linear calculations with reworked points is the soft spot
	- set them all to 100% then lower it in the event.ini files


