# Scoop Bucket for SynapSeq

This repository provides the official [Scoop](https://scoop.sh) manifest for installing **SynapSeq**,
the open-source brainwave sequencing engine built in Go.

## Installation

Add the SynapSeq bucket and install SynapSeq using the following commands:

```powershell
scoop bucket add synapseq https://github.com/ruanklein/scoop-synapseq
scoop install synapseq
```

After installation, verify the installation by running:

```powershell
synapseq -version
```

# Manifest Details

The manifest currently supports both `amd64` and `arm64` architectures on Windows.

The manifest automatically downloads the precompiled binaries from the [latest Github release](https://github.com/ruanklein/synapseq/releases/latest).

## Issues and Support

For reporting bugs or suggesting improvements related to installation, packaging, or distribution, please open an issue in the main SynapSeq repository using the  
[`type: packaging`](https://github.com/ruanklein/synapseq/issues?q=is%3Aissue+label%3A%22type%3A+packaging%22) label.

[Go to SynapSeq Issues](https://github.com/ruanklein/synapseq/issues/new?labels=type%3A+packaging&title=%5Bpackaging%5D%3A+)

## License

SynapSeq is licensed under the [GPL-2.0](https://opensource.org/licenses/GPL-2.0) license.
