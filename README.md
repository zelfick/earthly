# Earthly
Here is a demo hello-world using earthly utility

To get started, please visit
https://docs.earthly.dev

Join our Slack community
https://earthly.dev/slack

Ideas to get inspired
https://github.com/earthly/earthly/tree/main/examples

# Requirements
Earthly installed and configured
git installed
Internet 

# Tutorials
# Go
in /tutorials/hellogo execute:
```earthly +docker```
This will build the image, then we can run:
```docker run --rm hellogo:latest```

# Javascript
in /tutorials/hellojs execute:
```earthly +docker```
This will build the image, then we can run:
```docker run --rm hellojs:latest```

# Java - need fix
in /tutorials/hellojava execute:
```earthly +docker```
This will build the image, then we can run:
```docker run --rm hellojava:latest```

# Python
in /tutorials/hellopy execute:
```earthly +docker```
This will build the image, then we can run:
```docker run --rm hellopy:latest```

# To run the hiworld example
# Run locally
earthly ./hiworld+hello
# Remotely from github
´´´earthly github.com/zelfick/earthly/hiworld+hello´´´

# To Run DosGames
Pass the name of the game as argument, accordingly to games in the eathfile
```earthly ./dosgames+dugeonmaster```