# go2docker

Experimental tool for automatically containerizing a Go project.

## Usage

```sh
go2docker godir dockerimage
```

## Example

```sh
./go2docker example/ example:0.1
docker run -it --rm example:0.1
```
