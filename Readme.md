# Drone Playground

## Introduction

Playground for drone.io

## Contents

- [Usage](#usage)

## Usage

### Docker Compose for Gogs

Start everything:

```bash
docker-compose -f docker-compose.gogs.yml up -d
```

Take note of the passwords in the compose file then configure gogs:

```bash
open http://localhost:3000
```

Login with Drone:

```bash
open http://localhost
```

### Docker Compose for Github
