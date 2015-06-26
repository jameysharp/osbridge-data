# Participants

- @jamey\_sharp
- @stagedtheology
- @tklee
- @galgeek
- @edrex

# Raw Data

...is what this repository contains.

Also here's the proposal json converted to a spreadsheet:
<https://docs.google.com/spreadsheets/d/1XZfB3b9_TfQ855yhBCEFHxtTeI9AX00rvj74py-vRp0/edit?usp=sharing>

# Questions

- Can we find like-minded people based on favorites?
- Can we generate BOF sessions in advance?
- Can we design a schedule to minimize conflicts among sessions?
  - Cost assignment (based on timestamp?)
  - HARD CONFLICTS: Speaker can't appear in multiple locations
- Can we optimize room size based on favorites?
- Do favorites predict attendance?
- Do clickthroughs on description predict attendance? (We don't have data, but maybe!)
- Can we (from full text description) predict:
  - level?
  - attendance?
  - \# of favorites?
  - track?
  - which talks will be accepted?

# Tools

- cplex
- linear programming: AMPL
- <http://www.neos-server.org/neos/solvers/> \<- web interface to solve LP/NLP/MILP directly
- ibm ilog studio
- coin or (repository)
- informs
- SMT solvers (e.g., solve sudoku puzzle based on initial values)
- Bayes' theorem!
- Tabu search: <https://en.wikipedia.org/wiki/Tabu_search>
