# cutadapt
Small compatibility-focused container for `cutadapt`.

## Quick Usage

```bash
# Pull the image
docker pull docker.io/picotainers/cutadapt:latest

# Run the tool
docker run --rm docker.io/picotainers/cutadapt:latest cutadapt --help
```

## How to use

```bash
docker run --rm -v "$(pwd):/data" docker.io/picotainers/cutadapt:latest cutadapt --help
```
