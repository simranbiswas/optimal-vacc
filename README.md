# Optimal Vaccination Sequencer for Corona Virus

* An analysis of the ongoing Corona outbreak reveals that transmission of the virus occurs
in social networks. A social network is represented as an undirected graph G = (V, E), where
V denotes the set of cities and E denotes the set of edges connecting the cities.

* At time t = 0, all the cities are vulnerable. At each instant of time t > 0, any vulnerable city v
which is connected to some infected city u (i.e. (u, v) ∈ E) also gets infected, unless it was
vaccinated at some time t'<= t.

* The aim of the project is to vaccinate cities optimally such that the vaccination rate is
maximum and the number of cities it spreads in time t is minimum.
