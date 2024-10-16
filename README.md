# IoM_APP_RELEASE
## Island Power App
The Island Power App has been developed by David G. Quirk, Behzad Hosseinzadeh and Francesco Piovesan in 2024 on behalf of the Energy and Sustainability Centre Isle of Man (ESC) and with the financial support of the Manx Lottery Trust.
Around one-quarter (25%) of the Island’s power demand is for electricity.  Pulrose power station can generate 20-85 MW, sufficient to provide all of the Island’s electricity, although some also comes from burning waste plus a small amount of hydro-electricity.  Every year the power station burns more than 80 million m3 of natural gas (methane) emitting around 230,000 tonnes of CO2.  It will reach the end of its life before 2035 and is actually due to be replaced entirely by low-carbon sources of power by 2030 – the challenge with this app.  To deal deal with surpluses and deficits of power from renewable energy sources, an important part is choosing the right amount of storage and interconnection (subsea cable to export and import power),
The database behind the app was built by David Quirk and John Boucher and the simulations were carried out by Francesco Piovesan and David Quirk.  As the number of options have almost 1.7 million permutations, Francesco also built a batch mode tool in Matlab to carry out multiple runs simultaneously and build a matrix of results which was added to the database ‘SQLite’, whilst David developed formulae to simplify the results.  Behzad Hosseinzadeh developed the app utilizing the results matrix and formulae from the database which were combined using the open-source graphical user interface ‘Qt QML’. The source code will be available at https://github.com/behzaadh/IoM_APP for users to analyse further.  Artwork was designed by Amalie Quirk.
Further information can be found at www.energysustainabilitycentre.im/knowledge-hub.  The actual data, the calculations and other material can be requested from David Quirk – dquirk@dtu.dk – who is also responsible for any inaccuracies or errors.  Suggestions for new technologies and improvements to the app can also be made to David.
## Abbreviations used
avg – average

Hydro – traditional hydro-electricity power plant

MW, MWh – megawatt (1000 kW), megawatt hours (1000 kWh)

kW, kWh – kilowatt, kilowatt hours (or a ‘unit’ of electricity)

Nuclear – nuclear fusion power plant using small modular reactors (SMRs)

CO2 – carbon dioxide
