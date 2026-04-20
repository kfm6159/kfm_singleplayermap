# Quake Map Design Explainer: Venetian Single-Player Level

## Step One: Finding a Theme

Every strong Quake map needs a clear sense of place. A theme acts as a filter for every decision: room shape, lighting, monster placement, pacing. Without one, a map becomes a collection of spaces instead of a world.

In 2025, I was lucky enough to visit Venice, Italy twice: for a day trip in January & for an entire week in July. Summertime in Venice is a hot, humid madhouse, full of tourists dragging massive luggage bags up and down the many footbridges and cobblestone walkways.

But during the rainy winter months, Venice is a dreamlike, otherworldly experience: its narrow alleys (some barely wide enough for two people) & large piazzas are empty & silent, save for the constant lapping of water in the canals, the occasional ringing of church bells, and the sound of your own footsteps on the cobblestone bouncing off the surrounding buildings. It's a city full of covered "sotoportego" (covered passageways, sometimes dark and narrow, which connect different parts of the city) that tunnel through building bases, canals winding through the island in place of streets, and hidden courtyards that can only be glimpsed through locked, wrought-iron gates. You turn a corner and find yourself on a dead-end bridge over black water with no idea where the open piazza went.

In the wintertime, Venice feels like the haunting, gothic city of my imagination, where plague doctors walked and the fool Fortunato is entombed behind a brick wall while seeking a cask of Amontillado. And from the moment I first set foot on the main island, I've wanted to design a game environment/level inspired by it. That feeling of wonder mixed with spatial confusion and low-grade unease maps directly onto what a Quake level should do to a player.

The theme is Venice. Specifically, the Venice you find at night or off-season: ancient, labyrinthine, and full of secrets.

## Step Two: Researching WADs

I searched through community WADs looking for textures that would fit my Venice concept. I wasn't too concerned with finding the right look, as Venice's gothic aesthetic fits right in with Quake's original vibe.

Requirements: aged stone and brick readable as centuries-old Italian masonry; dark flagstone for canal-side paths; Gothic architectural detailing translatable to Venetian contexts; metal grating and ironwork for doors, bridges, and canal edges; and dark surfaces suggesting water, shadows, and damp interiors.

** Strong candidates included id1's rough stonework for dungeon-beneath-the-city areas, sock/medieval for high-detail Gothic palazzo facades and bridge arches, and Arcane Dimensions textures for large-format tiles and architectural accents in courtyard and canal zones. This research pushed the map toward something specifically Venetian in feeling, even within Quake's visual language.

## Step Three: Gameplay Themes

I worked through four emotional targets and thought about how the Venice setting could serve each one:

#### The player should feel like a hero.
Grand piazzas and canal vistas create natural arrival moments & visual set pieces. After tight calle and tunnels, opening onto a wide bridge overlooking a canal (with enemies ahead) gives the player a stage. Sight lines across water allow long-range engagement with the thunderbolt or super nailgun. These are showpiece moments.

#### The player should feel anxious and tense.
Walking around Venice is disorienting. The streets meander and branch; there are no street signs; dead ends appear without warning; narrow alleys are lined with buildings that are 7 or 8 stories high with dark windows that make you wonder if you're being watched. The map keeps navigation slightly ambiguous. Sound design (echoing water, distant footsteps, church bells) reinforces the sense that things are nearby even when invisible.

#### The player should feel isolated.
Venice empties out. Long stretches of calle with no enemies. Sight lines that reveal large open spaces with nothing moving in them. The city feels like it was full of people very recently. Interiors with set tables, unmade beds, and belongings left mid-use. The scale of the buildings dwarfs the player. Wide canal views with no way across and nothing on the other side. Silence as a design tool: the map gives the player room to feel genuinely alone before it takes that away.

#### The player should feel clever.
Venice is full of secrets like locked courtyards, shuttered passages visible from the canal but unreachable at street level. The map rewards spatial thinking. A bridge lowered by shooting a lever across the canal, a key hidden in a flooded basement visible only through a grate from above.

## Step Four: World Questions

To give the map internal logic, I worked through questions from Dungeon World and Level Design for Combat. Specific answers produce better environmental storytelling.

#### Where is this place in the world?
An ancient canal district in a city built on water, occupied and corrupted by Quake's interdimensional forces. The city existed before the invasion. The buildings remain exactly as they were. The monsters have moved into a human place and left it largely intact, which makes the occupation feel more sinister than obvious destruction would.

#### What happened here recently?
The city's defenders made a last stand on the main canal bridge and failed. Scorched stonework, a pushed-aside barricade of overturned market stalls, and weapons half-submerged in the shallows mark the site. The Quake forces passed through recently enough that candles inside some buildings are still burning.

#### What is about to happen?
The player's arrival has triggered the awakening of a dormant entity sealed in the flooded crypt beneath the district's oldest church. Enemies throughout the map are reacting — pulling back from outer positions, converging toward the center. The player is unknowingly racing this process, expressed through enemy behavior rather than a timer.

#### What should the player be on the lookout for?
Grated openings in canal walls hiding rooms below the waterline. Balconies above that enemies use for high-ground advantage. Doors accessible from adjacent rooftops. Iron sconces that function as levers. Any arch that looks decorative — at least one conceals a passage.

#### Who's really in control here?
Something older than the invasion. A Quake-aligned entity sealed beneath the city centuries ago, which the invasion gave an opportunity to wake up. It has been slowly corrupting the stone from below. Certain walls feel slightly wrong. Certain rooms feel like they want to close in.

#### What here is not what it appears to be?
The canal. The water is deeper than it looks, and the bottom is not visible. Falling in doesn't cause damage, but it alerts the entity below. One building looks collapsed and inaccessible, but it's the safest building in the map.

#### What rooms does this area normally contain?
Narrow calle connecting larger campo (open squares). Ground-floor commercial spaces with high ceilings, once used as shops and warehouses. Piano nobile floors above with formal rooms and balconies. Rear servant stairs. Private courtyard gardens behind blank exterior walls. Covered sottoporteghi through building masses. Canal-facing androne (water gates) at building bases. Partially flooded crypts and cisterns below.

#### Where is the toilet?
In Venetian buildings of this period, waste disposal ran through a small chute directly into the canal — a closet or alcove at the rear of the building, low ceiling, single exit. In the map, these spaces become tight side-passages ideal for hiding secrets or staging ambush encounters. Just don't think about what they're used for. ;)

#### How does it connect to other spaces?
No straight lines. Canal crossings require bridges controlled by levers or reached via rooftop. Underground cisterns connect buildings with no above-ground adjacency. Sottoporteghi create passages through building masses that make two distant-looking spaces a twenty-second walk apart.

#### What is its architectural style?
Venetian Gothic. Pointed arches on windows and water gates, brick construction with decorative marble facing on prominent facades, external staircases in larger courtyards, wooden beam ceilings. The oldest foundations are Romanesque — rounded arches in the crypts, heavy undressed stone. On top of that, the invasion has left runic markings scorched into walls at threshold points, metal grating across previously open openings, and a faint bioluminescent growth on the lowest stone surfaces near the canal.

