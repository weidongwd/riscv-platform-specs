# RISC-V Platform Specification

The files in this project are used to create the RISC-V 
Platform Specification.  This specification defines the set of firmware
and hardware required of a RISC-V platform so that it may install
and run various operating systems.

The content of the specification is created and controlled by the RISC-V
Platform Horizontal Subcommittee (RISC-V Platform HSC).  Information
about the subcommittee can be found at
https://lists.riscv.org/g/tech-unixplatformspec.
Please note that membership in RISC-V International is required to post
to the mailing list, but it is publicly readable.  Membership in RISC-V
International is free for individual community members.

All discussion of this specification occurs on the task group mailing
list.  Please use github issues for bug reports.

# Licensing

The files in this repository are licensed under the Creative Commons
Attribution 4.0 International License (CC-BY 4.0).  The full license
text is available at https://creativecommons.org/licenses/by/4.0/.

# Copyright information

This RISC-V Platform Specification is

&copy; 2017 Krste Asanovic &lt;<krste@sifive.com>&gt; \
&copy; 2017-2019 Palmer Dabbelt &lt;<palmer@sifive.com>&gt; \
&copy; 2017 Andrew Waterman &lt;<andrew@sifive.com>&gt; \
&copy; 2020 Al Stone &lt;<ahs3@redhat.com>&gt; \
&copy; 2021 Kumar Sankaran &lt;<ksankaran@ventanamicro.com>&gt;

# Repository Content
* **Makefile** => 'make' in this directory will produce the HTML, markdown,
and PDF versions of the current spec
* **README.md** => this file
* ```riscv-platform-spec.adoc``` => the spec in asciidoc format; there are
several subsidiary asciidoc files that get included by this file.

# Repository Branches
* All development occurs on ```main```; no content on main is to be
considered TSC-approved content.
* TSC-approved content will be clearly marked as such.

