# Daffy Pond
Daffy pond is an development docker environment for DaFFy project

## Installation

**Requirements:** Containers expose port 80 on the host so it has to be available.

Ensure you don't have app folder in project root, than run script:

```
./bin/install
```

It will clone the DaFFy project into app dir. After that it will build containers and start services.
Composer install also will be executed. After this script you should have running development version
of the DaFFy under `http://localhost`.
