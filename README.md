# nrc-site-2026

Static site for the Northwind Research Collective.  The catalogue of field
programme items lives in `_projects/`: one Markdown entry per item, with YAML
front matter carrying `title`, `kind`, `status`, `programme`, `notice_ref`,
`summary` and, when a released code artifact exists, `artifact_url`.

Edits to catalogue entries are made by changing the front matter only; the
body of each entry is generated from the summary at build time.

Release artifacts live in repositories under the collective's account.  Each
repository's README records its release status; read it before treating a
repository as a released artifact.
