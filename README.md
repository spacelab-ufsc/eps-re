<h1 align="center">
	RELIABILITY ENHANCED ELECTRICAL POWER SYSTEM (RE²PS)
	<br>
</h1>

<p align="center">
    <a href="https://github.com/spacelab-ufsc/spacelab#versioning"><img alt="Static Badge" src="https://img.shields.io/badge/status-in_development-red"></a>
    <a href="https://github.com/spacelab-ufsc/eps-re/releases"><img alt="GitHub Release" src="https://img.shields.io/github/v/release/spacelab-ufsc/eps-re"></a>
    <a href="https://github.com/spacelab-ufsc/eps-re/commits/master"><img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/spacelab-ufsc/eps-re"></a>
    <a href="https://github.com/spacelab-ufsc/eps-re/issues"><img alt="GitHub Issues or Pull Requests" src="https://img.shields.io/github/issues/spacelab-ufsc/eps-re"></a>
    <a href="https://github.com/spacelab-ufsc/eps-re/pulls"><img alt="GitHub Issues or Pull Requests" src="https://img.shields.io/github/issues-pr/spacelab-ufsc/eps-re"></a>
    <a href="https://github.com/spacelab-ufsc/eps-re/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/spacelab-ufsc/eps-re"></a>
</p>

<details>
    <summary><b>Summary</b></summary>
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
The **RE²PS** [[1]](#1) was designed to collect, store, and distribute energy for future SpaceLab missions, with a focus on increased robustness and reliability. Initially developed to support 1U and 2U CubeSats, this EPS can interface with up to 10 solar panels attached to the structure. It is also capable of operating the solar panels at their maximum power point (MPP). The collected energy is stored in lithium-ion batteries, and power distribution is managed by integrated DC-DC converters, generating 5V and 3.3V buses. This model is predominantly analog, enhancing its reliability in the challenging space environment. It also features redundancies in its energy harvesting unit (EHU) and power distribution unit (PDU).

<p align="center">
    <img src="https://github.com/spacelab-ufsc/eps-re/blob/master/figs/top.png"><img src="https://github.com/spacelab-ufsc/eps-re/blob/master/figs/bottom.png">
</p>

<p align="center">
    <a href="https://github.com/spacelab-ufsc/eps-re/issues/new?labels=bug"><img alt="Static Badge" src="https://img.shields.io/badge/Report_a_bug-red"></a>
    <a href="https://github.com/spacelab-ufsc/eps-re/issues/new?labels=enhancement"><img alt="Static Badge" src="https://img.shields.io/badge/Request_a_feature-yellow"></a>
    <a href="https://github.com/spacelab-ufsc/eps-re/issues/new?labels=question,help+wanted"><img alt="Static Badge" src="https://img.shields.io/badge/Request_more_information_or_help-green"></a>
</p>

## Repository Organization
`documentation`: Technical RE²PS's documentation.

`hardware`: RE²PS's hardware project (sources and outputs).

## License
This project is open-source under two different licenses: CERN Open Hardware License v2.0 for hardware and CC BY-SA 4.0 for documentation.

## Releases

Releases are published after verifying that all components of the project — hardware, firmware, and documentation — are synchronized and compatible, ensuring functionality and cohesion. Using different versions of hardware, firmware, or documentation projects can lead to misunderstandings or unpredictable behavior. Please refer to the **documentation** for more details.

## Notes
For more info about the SpaceLab, access our [GitHub](https://github.com/spacelab-ufsc/spacelab), [Linkedin](https://br.linkedin.com/company/spacelab-ufsc) or our [website](https://spacelab.ufsc.br/en/home/).

## References
<a id="1">[1]</a> D. L. Figueiredo, "Reliability Enhanced Electrical Power System for Nanosatellites," in <i>Repositório Institucional da UFSC</i>, pp. 1-85, 2023, available at <a href="https://repositorio.ufsc.br/bitstream/handle/123456789/247559/PEEL2103-D.pdf?sequence=1&isAllowed=y"> this link</a>.
