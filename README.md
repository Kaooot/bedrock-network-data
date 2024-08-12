# bedrock-network-data

This repository contains network protocol data that is essential for the operation of a Minecraft server.

### Table of contents

* [Releases](release/release-versions.md)

* [Previews](preview/preview-versions.md)

### Notice

Since version 1.21.10.22 (v704) the block palette is not in the correct
order. You can only use the hashed runtime ids specified in the block palette itself
and ``StartGamePacket#blockNetworkIdsAreHashes``must be set to true to use the block palette. This should not
be a problem as since version 1.19.80 (v582) hashed runtime identifiers should be used instead of a runtime id counter.

In addition, the following files have been removed as they can no longer be extracted:
* block_properties.json
* command_parameters.json
* item_properties.json
* particles.json
* sounds.json
* packetIds.md