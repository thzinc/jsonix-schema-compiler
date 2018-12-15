# jsonix-schema-compiler

This is a handy Docker image that wraps the schema compiler library that is part of [Jsonix](https://github.com/highsource/jsonix).

## Quickstart

Run the Docker image

```bash
docker run --rm -v `pwd`:/data thzinc/jsonix-schema-compiler -generateJsonSchema -p MySchema MySchema.xsd
```

More info on the command-line options in the [Jsonix Wiki](https://github.com/highsource/jsonix/wiki/Generating-Mappings-from-XML-Schemas)

## Building

[![Docker Build Status](https://img.shields.io/docker/automated/thzinc/jsonix-schema-compiler.svg)](https://hub.docker.com/r/thzinc/jsonix-schema-compiler/)

```bash
docker build -t tagname .
```

## Code of Conduct

We are committed to fostering an open and welcoming environment. Please read our [code of conduct](CODE_OF_CONDUCT.md) before participating in or contributing to this project.

## Contributing

We welcome contributions and collaboration on this project. Please read our [contributor's guide](CONTRIBUTING.md) to understand how best to work with us.

## License and Authors

[![Daniel James logo](https://secure.gravatar.com/avatar/eaeac922b9f3cc9fd18cb9629b9e79f6.png?size=16) Daniel James](https://thzinc.com)

[![license](https://img.shields.io/github/license/thzinc/jsonix-schema-compiler.svg)](https://github.com/thzinc/jsonix-schema-compiler/blob/master/LICENSE)
[![GitHub contributors](https://img.shields.io/github/contributors/thzinc/jsonix-schema-compiler.svg)](https://github.com/thzinc/jsonix-schema-compiler/graphs/contributors)

This software is made available by Daniel James under the MIT license.
