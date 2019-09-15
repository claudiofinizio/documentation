# README #

This is an announcement about a forthcoming computer software package dealing with the hydraulics of **rural** water supply schemes.

### What is this repository for? ###

The computer software is capable of finding an optimal sequence of pipes in order to minimize the investments costs.  

This is particularly important given the strong dependency of costs from parameters such as diameters and flows.  

Such software is most suitable for rural water supply schemes in the realm of humanitarian/development interventions, such as those financed by organizations such as the United Nations.   

The peculiarity of this package is the capability to deal with plastic pipes, which are typical of rural water supply schemes. With plastic pipes, the optimization problem becomes mathematically complex. Indeed, plastic pipes entail the introduction of discrete classes of rated working pressure and this makes the optimization of such system a non-convex problem, so it is not possible to optimize it using linear programing techniques (such as the Simplex method).  


### How do I get set up? ###

The software package will be released soon in public under a public GNU license, and will be contained in four repositories whose names are self-descriptive: persistence, frontend, logic and commons. A fifth repository, called documentation, will also be present.  

### Contribution guidelines ###

Contributions are welcome in the following aspects of the software:
- The creation of an intuitive user interface but rigorous to allow the data input, which will be based on open street map and will allow to draw the water supply directly on the screen.
- The social part of the application that will allow the different users to share knowledge and hints about design and also allow to share among users suggestions for a specific water supply scheme to be designed.
- Contributors with knowledge of numpy and scipy would also be welcome for some aspects of the mathematics in the software algorithms.


### Who do I talk to? ###

Claudio Finizio, is the owner of the project and welcomes anybody with an interest in humanitarian development, and specifically in the optimization of engineering systems to make the most of the limited financial resources.

_A short bio of Claudio_   

_Claudio is a chartered engineer who worked overseas in human development in Africa and the Middle East._

_He has 12 years of experience in water supply and sanitation and is currently working as freelancer on developing a computer software package to optimize the design of small rural water supplies. He was member of American Water Works Association and International Water Association._

_Aside competency in water supply, Claudio also brings 5 years of experience dealing with public administration. Recruited by the United Nations and later by the World Bank in Mauritania, he was primarily involved analysis of financial aid and performance of Ministries. He then contributed conceiving and delivering the online progress monitoring system for World Bank Romania Country Office._

_Previously he served non-governmental organizations in Tanzania, Afghanistan desert and in Palestinian refugees’ camps. He worked in isolated areas for prolonged periods._

### Timeline and future steps ###
End of 2019: publication of the source code with tests
Summer 2020: activation of the web-based user interface

End of 2019: lauching a fund raising campaign to finance the project.
The fund raising campaign is foreseen if the user itnerface will result too heavy to be programmed only based on free contributions from open source programmers.
