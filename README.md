# Java-template

## How to operate docker
### setup
1. Install with : `git clone`
### docker configuration
1. `docker compose up -d --build`
### Connect to and disconnect from docker
1. connect : `docker compose exec <service name(ex:base)> bash`
2. disconect : `exit`
### Starting and Stopping Containers
1. Starting : `docker stop <container name>`
2. Stopping : `docker start <container name>`

## Directory structure
```text
./
├── .dockerignore
├── .git
├── .gitattributes
├── .github
├── .gitignore
├── .pre-commit-config.yaml
├── LICENSE
├── Makefile
├── README.md
├── compose.yaml
├── config
├── data
│   ├── misc
│   ├── outputs
│   └── raw
├── docker
├── docs
├── env.sample
├── scripts
├── src
└── tests
```
