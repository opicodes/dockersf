# dockersf
Simple docker config to include in symfony projects

## Steps
Rename (*or even better copy*) .env.example to .env and set the variables for docker-compose.

#### Notes:
Redis is bound to 0.0.0.0 and had protected-mode disabled. Also no password is set. This makes this setup not suitable for **production** enviroments.