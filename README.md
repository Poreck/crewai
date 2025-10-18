.......... Install crewai on ubuntu ...........
First install uv tool
   curl -LsSf https://astral.sh/uv/install.sh | bash
then install crewai
   uv tool install crewai
   uv tool list   # Pour verifier la bonne installation de crewai
start crewai project:
   crewai create crew project_name
   cd project_name
   crewai install  # installer toutes les depnedencies du projets du fichier pyproject.toml (l'equivalent du fichier packages.json)
   ... customize the concerned files
   crewai run   # to lunch project
