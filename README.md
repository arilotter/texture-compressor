# Texture compressor

CLI tool for texture compression using ASTC, ETC, PVRTC and S3TC in KTX, DDS or PVR containers.

## Texture tester

A texture tester is available on https://timvanscherpenzeel.github.io/texture-compressor/.

## Status

	Work in progress

## Example

	General:
	-i, --input ./docs/example.png
	-o, --output ./docs/example.dds
	-m, --method s3tc
	-c, --compression dxt5

	Optional:
	-f, --flags "mipmode none" "quality 100"

    node ./bin/texture-compressor.js -i ./docs/example.png -o ./docs/example-dxt5.dds -m s3tc -c dxt5 -f "mipmode none" "quality 100"

## Licence

[Released under Apache-2.0](https://raw.githubusercontent.com/TimvanScherpenzeel/texture-compressor/master/LICENCE)
