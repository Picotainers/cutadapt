# cutadapt
Source-built container image for `cutadapt`.

## Quick Usage

```bash
docker pull docker.io/picotainers/cutadapt:latest
docker run --rm docker.io/picotainers/cutadapt:latest cutadapt --help
```

## Usage

```bash
# Mount the current directory so Cutadapt can read input FASTQ files and write output files
docker run --rm -v "$(pwd):/data" -w /data docker.io/picotainers/cutadapt:latest cutadapt -a ADAPTER -o trimmed.fastq reads.fastq
```

## Building

```bash
docker build -t docker.io/picotainers/cutadapt:latest .
```
