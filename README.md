# zhangyy0423.github.io — Personal Homepage

Live: **https://zhangyy0423.github.io**

## Structure
- `index.html` — single-page homepage (Publications / Research / Artifacts / Patent / CV)
- `cv/cv-yuyu-zhang.pdf` — CV PDF (update per season)

## Update procedure
```bash
cd ~/Documents/Codex/github/zhangyy0423.github.io
# edit index.html, then:
git add -A && git commit -m "update: <what>" && git push
# live in ~1 min
```

## Data source of truth (do not invent)
- Papers/arXiv IDs: project paper-line session state (docs/session-state-paper-*.md)
- DOIs: doi1-benchmark / doi2-audit-protocol Zenodo records
- Patent: CNIPA 2026114949359
- ORCID: 0009-0006-7430-6039
- Email: zhangyy0423@foxmail.com

## v1.1 (2026-10-18)
- Publications +1: university-era journal paper (JME 2022, 2nd author, DOI 10.11868/j.issn.1001-4381.2020.000244)
- New section: Industry Experience (GaiaDB/Baidu, GaussDB/Huawei, MCC Baosteel, Hesai)
- Education & awards merged into CV section
- Bilingual CV rendered (cv/cv-yuyu-zhang.pdf, 2pp, XeLaTeX ctex)
