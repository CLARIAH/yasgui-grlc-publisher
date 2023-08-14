# yasgui-grlc-publisher
### Yasgui plugin voor saving SPARQL queries to Github with grlc metadata tags

#### Run locally (with Docker installed)

---
    docker compose up

In the current setting of the docker compose file the application will run on http://localhost:8091


#### Context

---

- Yasgui SPARQL editor (Triply)
  1. [Documentation](https://triply.cc/docs/yasgui/)
  2. [Editor](https://yasgui.triply.cc/)
- GRLC
  1. [Homepage](https://grlc.io/)
  2. [Code and tutorial](https://github.com/CLARIAH/grlc/tree/dev#decorator-syntax)


#### Howto Install

---
1. [Download and install](https://www.docker.com/) docker for your operating system (e.g. Windows)
2. [Create](https://github.com/join) a Github account
3. Login to your github account and create a repository.
4. Click on your icon (top right), settings, developer settings (bottom left pane), personal acces tokens, tokens (classic), 'generate a new token'. 
5. Open a terminal (command prompt on Windows) and clone this repository by typing ```git clone https://github.com/knaw-huc/sparql-query-builder.git```
6. Move to directory by typing: ```cd yasgui-grlc-publisher```
7. Next type: ```docker compose up```
8. When you no longer see text running in the terminal, open up a browser and goto ```http://localhost:8091```
9. Run a query (you can just press the 'play' button on the right hand side) and then click 'publisher'
10. Now fill out all the requested details. Mime and Pagination can be left blank. Method can be set to 'get' if unsure.
11. Next click publish and wait for the query and metadata to be stored.
12. Once done, you see a link to grlc, where you can see your query and execute it. Obviously, you can also check the git repo to see the query enriched with grlc metadata.




