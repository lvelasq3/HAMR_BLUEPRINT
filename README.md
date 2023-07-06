# HAMR_BLUEPRINT
Solidpart and STL Files for the HAMR Blueprint Modular Prosthesis 

README – TDAP Socket, Hand, & Haptics Hardware
Last updated: May 2023
Katie Bomhoff, kbomhof1@jh.edu
Bypass Socket 

•	The bypass socket is the segment of the Tendon-Driven Anthropomorphic Prosthesis (TDAP) that is worn over the forearm, wrist, and hand of an intact limb. All files are included.

•	Current sockets: rigid socket (v9), flexible socket (v3)

o	Rigid v9 – full-size rigid socket for experimentation; hexagonal lattice allows for airflow while also allowing for haptic modalities to contact the skin; two pieces are held together with magnets (see inventory spreadsheet for exact magnets) that travel through a slot on one piece

Files

•	Socket_v9_lattice – basic lattice piece without motor mounts

•	Socket_v9_lattice_withmotors – lattice piece with integrated motor mounts

•	Socket_v9_wrist – wrist cover piece

•	Hand mount connector – printable adapter for wrist cover to hand connection


3D printing instructions
•	Print both parts in ABS on the robotorium Stratsys
•	Chem bath may be used for the lattice piece but NOT for the wrist cover, as chemicals can seep into voids in the thicker portions

Assembly instructions
•	Superglue magnets into designated voids. Make sure the correct poles will be facing each other so the magnets stick when pieces are assembled.
•	Allow to dry COMPLETELY before assembling pieces.
•	Slide wrist cover onto lattice through slot until magnets come into contact.
o	Flex v3 – mini full strap flex lattice; made up of two parts, the flexible TPU strap & the rigid connectors (tough PLA preferred); straps come in longer lengths to allow a variable radius towards the proximal forearm

Files
•	Half_strap – to be printed; is half the length of the strap for printing convenience
•	Half_strap1 – adds one connector per half strap (i.e. 2 connectors longer than original)
•	Half_strap2 – adds two connectors per half strap (i.e. 4 connectors longer than original
•	Half_strap3 – adds three connectors per half strap (i.e. 6 connectors longer than original
•	Strap_connector – normal connector that links two straps
•	Strap_expander – connector with one connection on one side and two on the other side to expand to a longer row
•	Support – rigid side supports to reduce buckling when connected to wrist cover

3D printing instructions
•	Straps: print in TPU 95A (Goose printer works best); Flow = 60; Temperature = 220; Disable retraction; Optimize path; Disable prime tower; Disable supports; Enable prime blob; Build plate adhesion = brim
•	Connectors & Extenders: print in tough PLA or other rigid material; Speed = 20; Disable retraction; Other settings default; 20-25 connectors per strap
 
	Assembly instructions
•	Press fit connectors into straps. Use two half straps with one connector to join them together. 
•	When expanding a row with longer straps, use an extender to connect one part on the row before with two parts on the new row.
•	Join ends together to form a circle. Continue adding rows and layers until desired length is reached. 
 
Motor mounts
o	Includes mounting hardware for Maxon re30 30mm motors. Correct sizes of screws are found in the inventory spreadsheet.
o	Also includes cufflink mechanism for non-integrated motor mounts.
o	All parts can be printed out of tough PLA with normal settings.

Old sockets
o	Rigid v1 – full print sockets; includes 3D model of previous clinical socket dimensions, updated curvature, and sockets with cuts/slits
o	Rigid v2 – press fit socket; includes two-part press fit
o	Rigid v3 – coaxial sockets; includes three-part coax and five-part coax connections
o	Rigid v4 – split wrist; includes wrist cover split in half for easier donning and doffing
o	Rigid v5 – camlock; includes a socket with camlock connection/mechanism
o	Rigid v6 – circle lattice; includes other lattice options for the socket, such as circle holes or no holes rather than the hexagonal holes
o	Rigid v7 – hook; includes a hooking mechanism with a slot on the lattice to hook into
o	Rigid v8 – ball & slot; includes oscilloscope type mechanism with a half sphere on one piece that slides into a slot on the other
o	Flex v1 – original flex lattice; includes wrist straps & half strap design
o	Flex v2 – full strap flex lattice; includes large size full strap design

3D Printed Hand
DIGIT	METACARPAL	PROXIMAL PHALANGE	MIDDLE PHALANGE	DISTAL PHALANGE
1 (THUMB)	MC1	PP1	N/A	DP1
2 (INDEX)	MC2	PP2	MP2	DP2
3 (MIDDLE)	MC3	PP3	MP3	DP3
4 (RING)	MC4	PP4	MP4	DP4
5 (PINKY)	MC5	PP5	MP5	DP5

•	The hand is 3D printed out of any rigid material with default settings. It is a right hand, but it can be mirrored for a left hand if necessary. The breakdown of part names for each digit is below.
•	List of carpal file names: captrap (represents capitate, trapezoid bones), hamatum (represents hamate, triquetrum, pisiform bones), lunoid (represents lunate, scaphoid bones)
o	*Note: trapezium bone represented on MC1 part
•	The parts involved in the thumb joint (for future work with dexterous thumb movement are the lunoid and the MC1.
•	All parts are present as STL files for printing; however, only the carpals, metacarpals, and distal phalanges are present as modifiable SLDPRT files.
•	3D finger models are included in their own folder. These were all taken from online resources for experimentation with flexible TPU fingers. 
•	Hand mounting hardware includes the negative mounting parts for sockets, as well as the adapter that can be printed out of nylon for attachment of socket to hand.

Haptics
•	Rice rocker models are included in the “haptics” folder. 
o	Single model & assembly is included, as well as rocker chain mechanisms, both in series and in parallel.
•	Hap_box 3D model is also included in the “haptics” folder as a three-level electronics box with swappable plates for connections and ports.

