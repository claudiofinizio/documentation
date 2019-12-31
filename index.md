# Rural Water #

This computer software package designs rural water supply schemes. It was conceived with the humanitarian and development interventions in mind.  <br/>
See demo: <http://ruralwater.pythonanywhere.com/>

## What does the computer software solve? ##

The **input data** are:
- the topology of each branch of the water supply, and the topography of the path
- the basic data about the borehole or the spring
- the list of pipes and hydraulic hardware which is locally available

The **output data** are:
- water flows and cost of each branch
- the sensitivity analysis between water flow and investment costs
- all hydraulic hardware parameters (diameters, choice of pumps, engines)

## How does it work? ##

Through a web app which is tailored for humanitarian interventions and non-professionals deployed in the field by humanitarian and development agencies

Who may benefit from the computer software?
- Donors (such as the **United Nations, Embassies**) may check through the web app those project proposals which allow more flexible solutions and/or make the best use of available money
- The **non-governmental organizations personnel**, that may present their projects through the web app and gain merit or ask for help by sharing online their project proposals in case of particularly difficult project designs



## Where it may result useful this web app?
- Water supply system for **humanitarian/development purposes of local communities**; examples would be villages scattered in Himalayan valleys, in the Andes or in the region of the Great Lakes in Africa.
  - _Typically_, deep valley profiles and all situations where pipe pressures require to make water flow by gravity through valleys and surpass hills.
- Small rural water supplies for scattered human settlements and farms such as those in rural United States or in the Australian outback.
  - _Typically_, adoption of dispacement pumps coupled to diesel engines
- Small irrigated fields owned by a family
  - _Typically_, in south east Asia, where optimizing the cost of lifting water from a  borehole is fundamental for a family of farmers to run its plot of irrigated land.


## Does this web app mimic other products?
No, so far this web app is unique. There are no specific rural computer software packages.
The web app deals with specific hydraulic hardware solutions for rural environments:
Rural water supply systems **differ markedly from urban schemes** since:
- they present a tree topology, they are not networks
- they adopt small size pipes which result in higher incidence of hydraulic friction
- they allow more wiggle room in deciding water flows since there are no requirements of redundancy, fire flow allowances and control of water age
- they adopt plastic pipes, whose cost differ markedly according to the pressure in the pipes
- they draw on gravity force or…
- …or make use of diesel engines and do not rely on electric power (so, electric pumps are often replaced by rotary pumps).



## The user interface of the web app
- Expatriate and local staff of humanitarian organizations often times are not engineers so the user interface will be simplified with the intent of guiding the user throughout the design process:
- the projects will reside in a main gallery, much like in a gallery of pictures
  - for each project, the user may experiment changing the various parameters of water demand or pumps and pipes; the web app will update the cost required for such a demand
  - when the user is satisfied with the design just obtained, s/he will “take a snapshot” of the project that will be added to the gallery of project.
  - At the end the user will choose one snapshot for each water supply system. This snapshot is the project that will be presented to the donors.
