# wireshark-thread-profile

Wireshark configuration profile for Thread traffic


## Installation

You can install this Thread profile by copying the `Thread` folder of this repository and pasting it inside the `profiles` folder of your Wireshark personal configuration directory.
In Linux distributions, this directory is typically located at `~/.config/wireshark`.
In this case, you can install it by executing the following commands:
```console
$ git clone https://github.com/akestoridis/wireshark-thread-profile.git
$ cp -r wireshark-thread-profile/Thread/ ~/.config/wireshark/profiles/Thread/
```
Regardless of your operating system, you can find the path of your Wireshark personal configuration directory by opening Wireshark, navigating to `Help`>`About Wireshark`>`Folders`, and inspecting the `Location` column of the `Personal configuration` row.
Once you have copied the `Thread` folder of this repository and pasted it inside the `profiles` folder of your Wireshark personal configuration directory, you can enable it by opening Wireshark, navigating to `Edit`>`Configuration Profiles...`, and selecting the `Thread` profile.


## Screenshots

The following screenshot showcases some of the profile's coloring rules, but several columns were hidden and the text was slightly enlarged to be more legible. A more detailed screenshot is available [here](https://github.com/akestoridis/wireshark-thread-profile/raw/d7110a6506e4417f9bf150632c8e5a1508f2ad3a/screenshot-wide.png).

<img src="https://github.com/akestoridis/wireshark-thread-profile/raw/d7110a6506e4417f9bf150632c8e5a1508f2ad3a/screenshot-narrow.png">

Both screenshots show the same packets from the `ot-nrf52840-pae-expt04.pcap` file of the [CRAWDAD dataset cmu/thread-devboards](https://doi.org/10.15783/xs01-4f07).


## Related Publications

* D.-G. Akestoridis, V. Sekar, and P. Tague, “On the security of Thread networks: Experimentation with OpenThread-enabled devices,” in *Proc. ACM WiSec’22*, 2022, pp. 233–244, doi: [10.1145/3507657.3528544](https://doi.org/10.1145/3507657.3528544).


## Acknowledgments

This project was supported in part by the Carnegie Mellon CyLab Security and Privacy Institute and in part by Carnegie Mellon University.


## License

Copyright (C) 2022 Dimitrios-Georgios Akestoridis

This project is licensed under the terms of the GNU General Public License version 2 or later (GPL-2.0-or-later).
