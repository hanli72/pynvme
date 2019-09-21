# pynvme
test NVMe devices in Python. [https://github.com/cranechu/pynvme]

[![Status](https://img.shields.io/gitlab/pipeline/cranechu/pynvme.svg)](https://gitlab.com/cranechu/pynvme/pipelines)
[![License](https://img.shields.io/github/license/cranechu/pynvme.svg)](https://github.com/cranechu/pynvme/blob/master/LICENSE)
[![Release](https://img.shields.io/github/release/cranechu/pynvme.svg)](https://github.com/cranechu/pynvme/releases)
[![Documentation Status](https://readthedocs.org/projects/pynvme/badge/?version=latest)](https://pynvme.readthedocs.io/?badge=latest)

<a href="http://www.youtube.com/watch?feature=player_embedded&v=NH6LmLSzjAs" target="_blank"><img align="right" src="https://github.com/cranechu/pynvme/raw/master/doc/logo.jpg" title="watch introduction video" alt="pynvme: test NVMe devices in Python" width="240" border="0" /></a>

The pynvme is a python extension module. Users can operate NVMe SSD intuitively in Python scripts. It is designed for NVMe SSD testing with performance considered. Integrated with third-party tools, vscode and pytest, pynvme provides a convenient and professional solution to test NVMe devices.

The pynvme wraps SPDK NVMe driver in a Python extension, with abstracted classes, e.g. Controller, Namespace, Qpair, Buffer, and IOWorker. With pynvme, users can operate NVMe devices intuitively, including:
1. access PCI configuration space
2. access NVMe registers in BAR space
3. send any NVMe admin/IO commands
4. callback functions are supported
5. MSIx interrupt is supported
6. transparent checksum verification for each LBA
7. IOWorker generates high-performance IO
8. integrated with pytest
9. integrated with VSCode
10. test multiple controllers, namespaces and qpairs simultaneously
11. test NVMe over TCP targets

Read the Doc of pynvme: https://pynvme.readthedocs.io/
PDF: https://buildmedia.readthedocs.org/media/pdf/pynvme/latest/pynvme.pdf
