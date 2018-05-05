## Game logic 

### Main goal
Divulgate open community science resources available online

### Game goal
The goal is that the player helps a community facing an environmental problem by providing information from open resources he can find online 

### Development

#### Opening screen
The screen shows a smartphone in the foreground (as if the player was holding it in his/her hand). Background image is post-apocalyptical scenario, no time reference. [Background image reference](art_references/background.jpeg)

On the phone screen, an app that looks like Signal. Messages start arriving from contact "community" (tbd)

- **MSG1** "we're leaving hospital now - Alex was feeling bad again, doctors tell us nothing can be done. It's something in the air that is causing all this people to feel sick"

- **MSG2** "We need to do something asap about this - Sasha told me you were joining the group, that's great. Let's see what we can think of together"

#### Screen 2
The screen is full of smoke ([image ref](art_references/smoke.jpeg)), some objects can be guessed but not properly seen behind it.

A piece of newspaper ([image ref](art_references/newspaper.jpg)) shows some news about the government allowing garbage burning and community concern & protests. 

#### Screen 3

- **MSG3** "The doctor told me that Alex's problem has to do with a special kind of dust in the air... Something called 'PM10'. We need more information about it"

- **MSG4** "Please bring back a useful URL about PM10. Use https:://duckduckgo.com search engine, I like my data as I like my coffee: UNTRACKED"

- **ACTION**: a blank box appears, where the player must paste a URL and click a button to submit

- **REPLY** (URL must contain words such as PM10+Air quality+health+pollution): 
a) That's not useful, try again, bring some reliable source of information    
b) That's useful, thanks!

#### Screen 4

- **MSG4**: "Ok so PM10 is a fine coarse dust that gets into the lungs and is terribly harmful for health... I guess other cities must have this same trouble. Let's see what's happening outside this town"

- **MSG5**: "Sasha sent me this cool site: https://waqi.info/... It collects data from official monitoring networks. Maybe you can tell me which city has the worst PM10 quality index? It would be useful to contact someone from there"

- **ACTION**: a blank box appears, where the player must enter name of the city

- **REPLY**: 
a) That's not right... Try again    
b) Hmm, interesting. We have some contacts there. 

#### Screen 5

- **MSG6**: "I also checked the map, these official data is a complete fraud! If you search for our town, they say the air is clean! We can't trust the government for this. We need to start monitoring air quality ourselves"

- **MSG7**: "My contact in Delhi mentioned a community where people build their own devices to monitor the environment. We need to see what this community is doing, go to their website https://publiclab.org/tags and bring me back the URL of the air-quality projects repository, please"

- **ACTION**: a blank box appears, where the player must enter URL https://publiclab.org/tag/air-quality

- **REPLY**: 
a) That's not right... Try again    
b) Perfect! There are many community projects about air quality!

#### Screen 6

- **MSG7**: "I was with Alex browsing the repository you brought and we found a cool project, it's well documented and I think we can replicate it with the materials we have at hand"

- **MSG8**: "We need the list of materials so we can gather everything and start working. I think this people have it somewhere in this collaborative platform called GitHub: https://github.com/rlyehlab/eter, an URL will do"

- **ACTION**: a blank box appears, where the player must enter URL https://github.com/rlyehlab/eter-monitor/blob/master/doc/BillOfMaterials.md

- **REPLY**: 
a) That's not right... Try again     
b) Next screen - END

#### Final screen

- **MSG9**: "We just checked and we have all the necessary to start building the device! I'll meet you tomorrow 7pm at the hacklab" 
