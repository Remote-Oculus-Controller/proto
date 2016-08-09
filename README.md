# proto
Repository for R.O.C protobuffers files

## Setup

The .proto present in this repository use proto3 syntax. [doc][proto doc]

[proto doc]:https://developers.google.com/protocol-buffers/

1. Get it

  Install protocol buffer libraire corresponding to the platform/languages you are using.
If you you are working in a linux environnement, your distribution repository might already have it.

2. Pull

  Pull this repository and add it to your project.

3. Make it

  Compile .proto for your language

  ```sh
  protoc --your_language=. ./*.proto
  ```

  All source file will be locate in the local folder see ```protoc --help``` for more information


## Use it

Under contruction
