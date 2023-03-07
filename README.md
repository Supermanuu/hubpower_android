
# HUB Power wrapper

This repository allows you to generate a hubpower binary for Android.

## Clone

This repo has to be cloned with recurse submodules or execute this after cloning:

```bash
git submodule update --init
```

## Build

To build a hubpower binary you need to run the following command:

```bash	
docker compose run --rm build
```

This will generate the binary in the `obj/local` directory, arranged by architecture.

## Clean

To clean the build you can do the following:

```bash
docker compose run --rm clean
```
