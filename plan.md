# 4OSS

## introductions

- we introduce ourselves
- participants introduce themselves
  - who they are, where they work
  - one top best practice for research software
- expectations for the workshop
- introduce Software Development Best Practices WG of ELIXIR tools platform, papers and 4OSS
- exercise (in pairs): challanges when reusing someone elses research software
- exercise (in pairs): challanges in making your own sofware open, what they did to make it easier for others to reuse their software
- exercise (pairs)
  - what are the fears of opening up the code?
  - what are the fears of contributing to someones code?

## make sources code publicly available from day one

- start with empty README.md file
- introduction to markdown
- https://opensource.guide
- exercise:
  - what is the advantage of making code open from day one vs when having first ready version of the software?
  - what are the disadvantages?
- exercise:
  - what is the minimum information necesary to document the software?
- exercise:
  - what is different audience of the documentation?
    - (end)users
      - novices
      - experts
    - developers
      - first time contributors
      - you one month later
    - collaborators
- there are different kinds of documentation
  - start with README.md
  - there are (web) tools/plarforms that make it easier:
    - sphinx
    - readthedocs
- release on github, connect to zenodo, get a DOI
- what other files?
  - CONTRIBUTING.md
  - CITE.cff
    - why citation?
    - we need recognition for software and that will not happen if there is no way to cite software
  - Code of Conduct
  - requirements.txt/environment.yml
  - CHANGELOG.md
  - metadata description (codemeta, schema.org, requirements by different journals eg. SoftwareX)
  - license
- other ways to increase reusability of your software
  - containers (biocontainers)
  - packaging


## choose a license

- you need a license from day one
- copyright vs license
- reuse existing license
- criteria for selecting the license
- choosealicense.com
- licenses and dependecies
  - license conflicts
  - relicensing
  - dual licensing (academic and commercial use)

## Define clear and transparent contribution, governance and communication processes

- Discussion: What are the benefits of having external contributions in your project?
- have you contributted to an external project?
  - how did it happen?
- Toby (owner) in the repo
    - find a typo
    - create and issue
    - labels it "good first contribution"
- Mateusz (collaborator)
    - look at contribution guidelines
    - fork
    - fix the typo
    - make a contribution
- Toby
  - merges
  - thanks for contribution
  - add the contributor to the contributors file
- what is the governance (discussion)?
  - responsibilities
  - bdfl
  - RFCs
- be kind to the contributors and have the guidelines (CONTRIBUTING.md)
- differnt kinds of documentation and their purpose
  - email
  - issues
  - wiki
  - stack overflow
  - gitter / slack / etc
  - irc

## Make software easy to discover by providing software metadata via a popular community registry

- why is discoverability of your software important
  - have you ever tried to find softare used in a paper? How easy was it?
- what is metadata?
  - why structured metadata (machine readibility)?
  - if you have structured citation info (.cff) you can pull all the citation info
  - example of metadata in R package (http://r-pkgs.had.co.nz/description.html)
- controlled vocabularies, ontologies etc
  - dublin core
  - schema.org
  - codemata
  - EDAM ontology
- software registries/repositories
  - GitHub
  - zenodo
  - Bio.tools
  - research software directory
- FAIR software
  - top 10 FAIR software things

## wrap up

- one up one down
- WWW / TALA
