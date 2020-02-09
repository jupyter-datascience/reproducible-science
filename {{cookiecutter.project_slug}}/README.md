{{cookiecutter.project_slug}}
==============================

{{cookiecutter.project_short_description}}

Project Organization
--------------------

```
  .
  ├── .env                       <- Computing environment for your code and third party tools (such as installing docker, sync files)
  │   ├── bin
  │   │   ├── get-docker.sh
  │   │   ├── get-miniconda3.sh
  │   │   ├── smartcdp
  │   │   ├── smartcdp-mac
  │   │   └── smartcdp.exe
  │   └── lib
  │   └── miniconda3              <- Environment for miniconda3 (all deps are installed into the directory, such choppy-pipe, choppy-report etc.)
  ├── bin                         <- Your compiled model code can be stored here (not tracked by git)
  ├── config                      <- Configuration files, e.g., for doxygen or for your model/scripts/tools if needed
  │   ├── choppy.conf.example
  │   ├── condarc.example
  │   └── smartcdp.conf.example
  ├── docs                        <- Documentation, e.g., how to use the project structure
  │   ├── beginner_guides
  │   ├── faqs
  │   ├── references
  │   ├── tutorials
  │   └── papers                  <- Scientific papers / manuscripts, e.g., how to use the project structure
  ├── immutable_data
  │   ├── examples
  │   ├── external                <- External data to the project
  │   ├── processed               <- The final, canonical data sets for modeling
  │   ├── publish                 <- Data to publish
  │   │   ├── article
  │   │   ├── choppy_report
  │   │   └── data_portal
  │   ├── rawdata
  │   ├── visualization
  │   └── README.md
  ├── interim_data                <- Intermediate data that has been transformed (not tracked by git)
  ├── notebooks                   <- Jupyter notebooks
  ├── pipelines                   <- Pipeline from choppy app in choppy-pipe
  │   └── README.md
  ├── reports                     <- For a manuscript source, e.g., LaTeX, Markdown, etc., or any project reports for choppy-report
  │   ├── data                    <- Link to ../immutable_data/publish/choppy_report
  │   ├── defaults                <- Default settings for choppy-report
  │   └── index.md                <- Report templates
  ├── scripts                     <- Source code for this project
  │   ├── data
  │   ├── external
  │   ├── models
  │   ├── tools
  │   └── visualization
  ├── .gitignore
  ├── AUTHORS.md
  ├── LICENSE
  ├── Makefile
  ├── README.md
  ├── conda_packages.txt
  └── requirements.txt
```