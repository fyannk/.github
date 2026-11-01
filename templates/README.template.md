<!--
fyannk README template v1 — copy to README.md and fill every {{…}}.
Delete sections marked (optional) that do not apply; keep the order of the rest.
Mark rules: PostgreSQL projects use the elephant, others the ermine or their own mark.
-->

<p align="center">
  <img src="{{path/to/logo.svg}}" width="140" alt="{{Project}} logo">
</p>

<h1 align="center">{{Project}}</h1>

<p align="center">
  <strong>{{One sentence: what it lets the reader do.}}</strong><br>
  {{One sentence: what makes it trustworthy or different.}}
</p>

<p align="center">
  <a href="https://github.com/fyannk/{{repo}}/actions/workflows/ci.yml"><img src="https://github.com/fyannk/{{repo}}/actions/workflows/ci.yml/badge.svg" alt="CI status"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-{{Apache--2.0}}-090c0a?style=flat-square&labelColor=1b231d" alt="{{Apache-2.0}} license"></a>
  <img src="https://img.shields.io/badge/{{Go}}-{{1.26}}-090c0a?style=flat-square&logo={{go}}&logoColor=b3bf3a&labelColor=1b231d" alt="{{Go 1.26}}">
  <img src="https://img.shields.io/badge/status-{{0.x pre--1.0}}-090c0a?style=flat-square&labelColor=1b231d" alt="{{Pre-1.0}}">
</p>

{{Project}} is {{a one-paragraph description: what it is, who it is for, and
where it runs. Plain words, no marketing.}}

> [!IMPORTANT]
> {{The boundary: what this project does NOT do or prove. Be honest about
> uncertainty, e.g. "reports what the operator claims; does not prove
> restoreability".}}

## Why use it?

- **{{Benefit}}**: {{one line}}
- **{{Benefit}}**: {{one line}}
- **{{Benefit}}**: {{one line}}

## What is included

| Component | Purpose |
|---|---|
| {{component}} | {{what it does}} |

## Quick start

Prerequisites: {{versions, cluster, credentials}}.

```sh
{{the shortest path from zero to something visible}}
```

{{What the reader should see when it works.}}

## Run it as a container (optional)

```sh
docker run --rm -p {{8080:8080}} ghcr.io/fyannk/{{repo}}:{{tag}}
```

## Configuration (optional)

| Setting | Default | Description |
|---|---|---|
| `{{FLAG_OR_ENV}}` | `{{default}}` | {{description}} |

## Limitations (optional)

- {{Known gap, and the workaround if there is one}}

## Project status

{{pre-1.0 / stable / maintenance only}}. {{What is stable, what may change.
Link the roadmap or changelog.}}

## Documentation

{{Link to the docs site, or the main docs folder.}}

## Contributing

Contributions are welcome. Read [CONTRIBUTING.md](CONTRIBUTING.md) first.
For larger changes, open an issue before writing code.

## Security

Report vulnerabilities privately, as described in [SECURITY.md](SECURITY.md).

## License

{{Apache-2.0}}. See [LICENSE](LICENSE).
