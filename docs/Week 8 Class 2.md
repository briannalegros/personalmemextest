Computational Incunabula: The BRitish Experience

Colossus
- developed during WW2
- emerged from the bombe
- never fully declassified until well after the war
- supervening necessity: German Wolfpack
- keeping shipping open
- avoiding german u-boats
- this meant the british really needed to break these german cyphers

Enigma
- based on the ideas used in a commercial machine developed by edward herbern
	- aimed at banks and business and anyone who didn't want their emssages to be read
- german: Arthur Scherbius: calls it his enigma, meaning riddle
- typewriter key, wired to lights showing letters
	- a become q
	- if you change the wiring with each keystroke, it becomes a polyalphabetic substituion cypher
	- easy to break with one rotor
	- 2 rotors makes 676 letters, but you only need to know 2 letters/numbers to set up to decrypt
	- 3 rotors make it to 17576 letters
- "Combining three rotors from a set of five, each of the 3 rotor setting with 26 positions, and the plug board with ten pairs of letters connected, the military Enigma has 158,962,555,217,826,360,000 (nearly 159 quintillion) different settings. (5 × 4 × 3) × (263) × [26! / (6! × 10! × 210)] = 158,962,555,217,826,360,000."
- Scherbius dies in cart accident in 1928
	- by mid 1930s every branch of the german military uses these machines
- no letter could be encryphered as itself
	- this enventually is the crack into the wedges driven to break the codes
- polish government sees what's coming down the pipe
	- they broke 3 roto machine by mid 30s
		- week sbefore the invasion
	- they shared what they knew with the french and germans
	- created a machine called the Bombas, basically reverse engineered the enigma
		- was no longer useful every time they added rotors to enigma

Hut 8 and Bletchly Park
- government code and cypher school
- turing and his crew worked here on the problem of crack the naval enigma machines
	- they knew in principles and had a good idea of its designs
- turing et al worked to improve the bombe machines
	- sepcilized calculators to breal the codes
- dozen of mathemeticians, 4 linguists and 100+ others who apparently were all women
- simpler machines were what most specialized electro-mechanical devices were what Zuse, Aitken and Mauchly
	- the need was much greater
- they focused on probable words
	- they were used as keys to set the rotors up
	- plaintext was used in some messages
	- the context eventually gave them a method to start to test possible keys
	- they'd sometimes spot messages that were less secure being resent on more secure machines
		- breaking it on a lesser machine would give a key to a stronger
- bombe would churn through the possibilities
	- in 1941 they could crack a message a day
- 1942 germans added another rotor
	- allies didn't know until a radio operator sent a message with one wheel turned off
	- he then corrected himself and sent the same message again with the wheel turned on, revealing existence of a new wheel

_"It was luck the security people didn't know [about Turing being gay] early on, because if they had known, he might not have obtained his clearnace and we might have lost the war"_ 
- Member of Turing's team

Bombe to Colossus
- Turing's teacher, Max NEwman lead the design of the Colossus
- Colossus could suggest best matches for patterns within a text
- second Colossus could figure out which pattern was best to try
- integrated valves of the key
- german encyption required more powerful devices as they kept improving their machines
- the british build a device that can do boolean operations
	- too similar to the analogue computers of Vannevar Bush
	- also involves valves and relays and paper tape readers
- was a rickety device, it didn;t have to be pretty, it just needed to work
- they worked on how to store the patterns to help search for more encoded messages in valves
	- so the messages they were intercepting could just be put on the same machine
- 1943 allies were able to neutralize german encryption again
	- shaves off 2-3 years of the war
- ENIAC and Colossus sit astride the phase transition from powerful calculators to full-on computers
- the difference is that a full on computer needs a datastore 
	- where its operating instructions are held
	- can be varied because of the calculation

Post War Developments Doldrums
- multiple teams are exploring these machines that sit on the calculator/computer barrier
- von Neumann write the 'First Draft of a Report on The EDVAC' 1945
- but for the most part, the urgency is gone; everyone losing steam, in terms of computing design
- last technical hurdle to solve is the problem of memory
- von Neumann's paper circulates widely
	- describes the kinds of things a computer should have
	- a writer said "It was as if, in the early 1890s, somebody had specified, in some detail, the fundamental design elements of an automobile - and that this document acted prescriptevily to limit the range of options available to engineers int he decades following"
- influenced turing, Mauchely, the Institute of Advanced Studies in Princeton, anyone who was into these devices read the report

From one supervening necessity to another
- project whirlwind
	- starts of as an analogue computer
	- menat to simulate flight on multiple airplanes being developed for the war
	- was one of the most expensive of the various computing projects
		- the navy lost interest
	- airforce takes over the project
		- only machine that could plot intercept courses for strategic long range bombers
	- solved the problem of magnetic memory
	- rejigged for real-time output and parallel processing
		- it could display its output on an oscilloscope in real time
	- it became the core of airdefense in NA
- led by Jay Forrester
	- devlops key ideas in system dynamics
	- this inspired Will Wright
		- encodes these into Sim City
	- he had dodgy ideas about urban values
		- those regressive ideas have now informed generations of gamers
- cold war provided new supervening necessity
	- new weapons, new simulators, new global-spanning aircrafts, missels and space all require computing power
- first ocmputer installed at the institute for advanced study in princeton
	- ready to go by 1951
	- one problem came from the Los Alamos nuclear folks, running 60 days 24/hrs a day
- the us had its research and industrial/military work distributed across labs and competitive research groups, many computers emerge, largely based on the design of the machine at IAS
	- all these mechaines have been programmed
	- the programming aproach for each designed and developed from scrastch
- soviet detonate atomic bomb in 1949
	- americans respond with h bomb in 1952
	- we need digital computers

MEanwhile in Britain
- manchester baby
- built to test another solution to the problem of memory
- runs a stored program from memory in 1948
	- another first computer moment
- the idea tjat all computers had to be big and monsterous meant that the machines that were quickly designed and relatively small despite working couldn't take off
	- remained a curiosity
	- returned to building big room filling machines

Allies no longer sharing info
- act of congress in 1946
	- closes off data sharing with allies over nuclear work
- briatin sets out to build its own now that they're shut off
- decides that all experiences should be centralised at the the national physical laboratory
- the official british computer will be built at the NPL and they turn to Turing to make it
	- names it the automatic computing engine as a hat tip to babbage
- work at manchester shows how successful britain's boffins were at controlling things
	- only got funding for the machines by saying it;d be used for physics and math research
		- similar gambit that von neumann used for getting computing work at the institute for adavanced studies in the us
	- minor official in the bureaucracy decided however that there was no use ACE and worked to obstruct turing
	- because of the official secrets act, Turing couldn't explain to this bureaucrat the signifance of what he was trying to do

Death of Alan Turing
- turing moves to manchester to work on computing 1948
- his house got burgled
	- he calls the police
	- his partner said that he thinks its a certain guy so he relays this to the police
	- he gets found out as a homosexual
	- he found guilty of gross indecency
		- was given a choice between imprisonment or probation with chemical castration
	- he loses security clearances, chooses castration
	- commits suicide 1954
	- pardoned in 2012
	- this guy saved britain
	- this made it so that britain couldn't trust people who were in secrecy
	- this paranoia destroyed britain's domestic computing industry
		- they tried to weed out owmen and other "unreliable types" in favor for public school educated old men
		- they women trained these types of people and took over their jobs
	- Harold Wilson mandates a nationalization of computing industry in 1965

The Period of The Digital Incunabula is Over
- in the UK, commerical versions of the manchester 'baby' are being sold by the ferranti corproation as general purpose business computers by 1951
- 1952, IAS machine comes online
- the digital age beings
- "There will never be enough problems, enough work for more than one or two of these computers... stop this foolishness with Eckert and Mauchly" - Aitken
- around this time that canada was introduced to computers

IBM finally gets in on the act
- indicidentally, on some accounts, this is when the digital humanities are born - Busa
- IBm repurposes existing devices
	- built a new computer
- psuhed into action by the way Rand was selling UNIVAC computers
- releases the '702' with help from von Neumann and the IAS people, in exchange for equipment

Programming still an issue
- every computer had its own wiring, circuits, designs, idiosyncracies
- people like Grace Hopper are building compilers and higher level languages to ease programming and provide some interoperability
- mostly male programmers liked the secrecy of the way things were
	- meant they relied on the mystery of it all to maintain the positions, priviledges
- these tasks were sensitive operations
	- they didn't know what they were doing
	- worked virtually in the open
	- secuirty always gets bolted on afterwards
- people used whirlwind computers developed a kind of language to work with it
- rgace hopperthe impetus behind the languages FORTRAN and BACAIV
- IBM builds FORTRAN into its machines starting around 1958

- Every machine is unique
- every machine is larger and more expensive
- living with the government's payment, both the funder and the buyer for these devices
- was this an effective use of money to build machines like this that could often stand comparatively idle
	- you needed to put programming on to them
	- lot of dead time because they were so fast
		- operations between operations didn't exist

Time for the Internet?
Competences:
- existence of digital computers
- existence of telecommunication networks
- existence of information theory
- ideas around flow control, logic, algorithms
- demonstration of control of a calculator over a phone line in 1940
- computers weren't doing much, so they began to tie them together
	- using multiple programs at the same time to timeshare
	- needed to show that they were using the machines

Grand Myth of the Internet
- "A system designed to prevent breakdown in the event of a nuclear war"