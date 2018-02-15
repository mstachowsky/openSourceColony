# Open Source Colony
A simulation framework for space colonization

## Project Overview
This project is concerned with creating a research-level simulation for deep space missions, for the purpose of testing various mission architectures, and comparing them with each other.  The project is **data-driven** and **evidence based**.  The missions to be simulated will be "end-to-end" - from development of hardware to return of cargo/resources/personnel to long-term benefits of the mission.

### Project Goals

1. To generate datasets from literature that allows us to simulate each of the above as accurately as possible given the current state of knoweldge.
2. To generate simulation software that allows us to run many simulations of the same architecture, accounting for various random variables, to determine the suitability of a particular mission architecture.
3. To generate meaningful comparisons of mission architectures, including quantitative metrics by which missions can be compared and evaluated.
4. To generate a user-friendly interface for creating, running, and evaluating missions.

### Desired simulations

The simulations include, at a minimum:

1. **Logistics** - getting resources and personnel from Earth to the mission location, including optional return.
    - Resource management: resources, resupply, ISRU
    - End-to-end considerations: To create as realistic a simulation of the development and delivery of resources to the mission location as possible, so that various architectures can be meaningfully comparted.  Simulating the benefits of ISRU over resupply, for example, will require consideration of moving the ISRU equipment to the mission location, development costs etc.  Orbital transfers and energy requirements also will factor in.
2. **Mission plans** - simulation of the achievement of mission milestones and scientific/economic returns.  A discrete-event simulation framework will be developed for this purpose.
3. **Actor simulations** - missions can be crewed, robotic, or a mixture of both.  Actors must be simulated in a data-driven way - we must be able to determine the real costs of supporting each type of actor, and the real benefits of each type.  Meaningful comparisons must be able to be made.  Interactions between intelligent agents acting in co-operation and independently will be considered.
4. **Human factors** - accurate simulations of mental health, group dynamics, expertise, health and life support, emergencies, fatigue and motivation etc. must be considered and compared.
5. **Hardware** - accurate simulation of various hardware components.  The creation of a dataset for realistic simulation of various components.  The creation of a software framework in which various hardware architectures can be simulated and compared.
6. **Mission support** - accurate simulation of the economics and requirements of Earth and space based mission support.  Includes economic simulations of hardware development and funding, public support/outreach etc.

### Datasets and data representation

The generation of datasets and a data representation framework will be crucial to this project.  A method by which parameters can be specified and used to compute must be developed.  The types of data needed, what needs to be simulated, and how it can work together in a coherent whole must be determined.
