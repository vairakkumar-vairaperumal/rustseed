# How to create a project development seed.

This repo provides a sample development environment for rust development.
This can be replaced with any other rust images and add any other development requirements

## Getting Started

1. Prerequisites

The following are requirements for development
 a. docker and docker-compose installed
 b. Git is Installed

2. Clone this repository

```
git clone "https://www.github.com/jaydevops/rustseed.git" testrust
```

3. Run docker-compose

```
cd testrust
docker-compose run rustseed
```

4. Remove git (run only time)

```
rm -rf .git
./setenv.sh
```

5. Run cargo init (required only when creating a new app)

```
cargo init testrust
```

6. Add to git repo

Do the following from the host
```
git add .
git commit -m "initial"
# git push "replace with your repo url"
```


