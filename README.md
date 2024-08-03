<h1 align="center">
	RELIABILITY ENHANCED ELECTRICAL POWER SYSTEM (RE²PS)
	<br>
</h1>

<p align="center">
    <a href="https://github.com/spacelab-ufsc/spacelab#versioning">
        <img alt="Static Badge" src="https://img.shields.io/badge/status-in_development-red">
    </a>
    <a href="https://github.com/spacelab-ufsc/eps-re/releases">
        <img alt="GitHub Release" src="https://img.shields.io/github/v/release/spacelab-ufsc/eps-re">
    </a>
    <a href="https://github.com/spacelab-ufsc/eps-re/commits/master">
        <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/spacelab-ufsc/eps-re">
    </a>
    <a href="https://github.com/spacelab-ufsc/eps-re/issues">
        <img alt="GitHub Issues or Pull Requests" src="https://img.shields.io/github/issues/spacelab-ufsc/eps-re">
    </a>
    <a href="https://github.com/spacelab-ufsc/eps-re/pulls">
        <img alt="GitHub Issues or Pull Requests" src="https://img.shields.io/github/issues-pr/spacelab-ufsc/eps-re">
    </a>
    <a href="https://github.com/spacelab-ufsc/eps-re/graphs/contributors">
        <img alt="GitHub contributors" src="https://img.shields.io/github/contributors/spacelab-ufsc/eps-re">
    </a>
</p>

<details>
    <summary>Summary</summary>
    <ol>
        <li>
            <a href="#overview">Overview</a>
        </li>
        <li>
            <a href="#repository-organization">Repository Organization</a>
        </li>
        <li>
            <a href="#license">License</a>
        </li>
        <li>
            <a href="#releases">Releases</a>
        </li>
        <li>
            <a href="#notes">Notes</a>
        </li>
        <li>
            <a href="#references">References</a>
        </li>
    </ol>
</details>

## Overview
The **RE²PS** [[1]](#1) has been designed to harvest, store and distribute energy for a future SpaceLab's mission. The energy harvesting system is based on solar energy conversion through 10 solar panels attached to the structure. This EPS is designed to operate the solar panels at their maximum power point. The harvested solar energy is stored in 4 lithium-ion batteries connected in series/parallel. The energy distribution is done by several integrated DC-DC converters. The EPS designed is almost all analog, and therefore more reliable when considering the impact of radiation on the system.

<p align="center">
    <img src="https://github.com/spacelab-ufsc/eps-re-documentation/blob/figures/flatsat2_3D.png">
</p>

<p align="center">
    <a href="https://github.com/spacelab-ufsc/eps-re/issues/new?labels=bug">
        <img alt="Static Badge" src="https://img.shields.io/badge/Report_a_bug-red">
    </a>
    <a href="https://github.com/spacelab-ufsc/eps-re/issues/new?labels=enhancement">
        <img alt="Static Badge" src="https://img.shields.io/badge/Request_a_feature-yellow">
    </a>
    <a href="https://github.com/spacelab-ufsc/eps-re/issues/new?labels=question,help+wanted">
        <img alt="Static Badge" src="https://img.shields.io/badge/Request_more_information_or_help-green">
    </a>
</p>

## Repository Organization
`documentation`: Technical RE²PS's documentation.

`hardware`: RE²PS's hardware project (sources and outputs).

## License
This project is open-source under three different licenses: CERN Open Hardware License v2.0 for hardware and CC BY-SA 4.0 for the documentation.

## Releases

Releases are made after verifying that all components of the project (hardware, firmware if applicable, and documentation) are compatible with each other and fully functional. Using different versions of hardware, firmware, and documentation projects may result in unpredictable behavior. See the [documentation](https://github.com/spacelab-ufsc/eps-re-documentation/tree/main) for more information.

## Notes
More info about the SpaceLab: [GitHub](https://github.com/spacelab-ufsc/spacelab) and [Website](https://spacelab.ufsc.br/en/home/).

## References
<a id="1">[1]</a> D. L. Figueiredo, "Reliability Enhanced Electrical Power System for Nanosatellites," in <i>Repositório Institucional da UFSC</i>, pp. 1-85, 2023, available at <a href="https://repositorio.ufsc.br/bitstream/handle/123456789/247559/PEEL2103-D.pdf?sequence=1&isAllowed=y"> this link</a>.
