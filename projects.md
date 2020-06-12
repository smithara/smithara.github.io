---
layout: default
---

---

# Some projects I am working on

---

My work is a mix of scientific research, software development, and consulting. I use ESA's [Swarm satellite constellation](https://earth.esa.int/eogateway/missions/swarm) which probes Earth's [magnetic field sources](https://magneticearth.org/pages/magsources.html) and the space environment at low Earth orbit.

I am employed as a post-doctoral research associate at the University of Edinburgh, UK, funded through Swarm DISC. Swarm DISC (Data Innovation & Science Cluster) is itself funded through ESA and comprises various partners at different institutions. Its task is to improve the scientific return of the Swarm mission through development of additional data products and services. My primary role is to assist with the development of the "Virtual Research Environment".

----

## ESA's Swarm mission data access tools: VirES & VRE

VirES is a data access, visualisation, and processing platform for the Swarm mission. It is developed for ESA by [EOX IT Services](https://eox.at) and is a free and open source project. I got involved initially by working as an intern at EOX in the summer of 2018. Try out the web interface: [VirES for Swarm](https://vires.services); or the upcoming [Aeolus version](https://aeolus.services).

I am responsible for building and maintaining the Python package "viresclient" which provides programmatic access to the Swarm data and models through VirES. This is deployed on the ["Virtual Research Environment" (VRE)](https://earth.esa.int/eogateway/tools/swarm-vre) which provides an easy way for scientists to start programming - this is a JupyterLab system backed by a curated Python environment and some notebook tutorials/recipes to help people get started.

### ``viresclient`` Python package

- [GitHub project page](https://github.com/ESA-VirES/VirES-Python-Client)
- [Documentation](https://viresclient.readthedocs.io)
- [Swarm DQW9 presentation (2019)](https://smithara.github.io/SwarmDQW9_viresclient_presentation/viresclient.slides.html)

### Virtual Research Environment (VRE)

- [VRE access](https://vre.vires.services)
- [User Documentation](https://swarm-vre.readthedocs.io)
- [Notebook repository](https://github.com/Swarm-DISC/Swarm_notebooks)

### Swarm quicklooks

I want to provide images showing recent data from Swarm, which are automatically updated every day. Initially these are simple figures which may be used for outreach, but over time may evolve into a dashboard useful to scientists and engineers working with Swarm. The code is [here](https://github.com/Swarm-DISC/Swarm_quicklooks) and figures are displayed [here](https://magneticearth.org/pages/quicklooks.html).

---

## Magnetic Earth

This is my attempt to provide a community-built resource to introduce geomagnetism - the science, the tools, and the organisations involved - which should be useful to new researchers and as a central location to link to more specific resources. The website is at <https://magneticearth.org>.
