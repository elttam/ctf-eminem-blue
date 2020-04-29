# Overview

**Title:** Eminem Blue (Backstabber)   
**Category:** Web  
**Flag:** `libctf{c8428414-6610-4ae8-af64-9f595fffbdef}`  
**Difficulty:** Medium-Hard

# Usage

The following will pull the latest 'elttam/ctf-eminem-blue' image from DockerHub, run a new container named 'libctfso-eminem-blue', and publish the vulnerable service on port 80:

```sh
docker run --rm \
  --publish 80:80 \
  --name libctfso-eminem-blue \
  elttam/ctf-eminem-blue:latest
```

# Build (Optional)

If you prefer to build the 'elttam/ctf-eminem-blue' image yourself you can do so first with:

```sh
docker build ${PWD} \
  --tag elttam/ctf-eminem-blue:latest
```