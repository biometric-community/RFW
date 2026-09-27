# RFW

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FRFW-181717?logo=github)](https://github.com/biometric-community/RFW)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](http://www.whdeng.cn/RFW/index.html)

**RFW** — tbiom catalog packaging for `rfw` (face-recog; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/RFW
- **Upstream source**: http://www.whdeng.cn/RFW/index.html
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `rfw` |
| Category | `face-recog` |
| Access | `register` |
| Upstream homepage | http://www.whdeng.cn/RFW/index.html |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: Racial Faces in the Wild.

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/RFW.git
cd RFW
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_rfw.sh
```

Place licensed archives under `projects/datasets/rfw/` (gitignored).

## Dataset structure

```text
RFW/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: http://www.whdeng.cn/RFW/index.html
- Packaging: https://github.com/biometric-community/RFW/issues
