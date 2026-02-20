# VALORADA Documentation

This repository contains source Markdown files for the VALORADA project documentation and an MkDocs configuration for building a documentation site.

## Structure

After restructuring:

```
mkdocs.yml
docs/
	index.md
	climate-impact-chains/
		index.md
		chain-urban-ecosystems.md
		chain-heat-health-transport.md
		chain-drought-agriculture.md
		chain-wildfire.md
		chain-floods-rural-livelihoods.md
	data/
		ecde.md
	framework/
		data-valuation-framework.md
```

Original source files (`cic.md`, `ecde.md`, `framework.md`) have been reorganised into thematic pages under `docs/`.

## Local Preview

Install dependencies and start the dev server:

```bash
pip install mkdocs mkdocs-material
mkdocs serve
```

Open http://127.0.0.1:8000 to view.

## Contributing
Edit or add pages under `docs/`. Maintain one H1 per page, provide descriptive alt text for images, and keep headings hierarchical. Submit PRs with clear rationale.

## License
Please add a license statement here if applicable.

## Acknowledgments

We acknowledge the use of GitHub Copilot, an AI-based code completion tool, which assisted in the conversion of documentation into markdown format.

## References

GitHub Copilot. GitHub, Inc. Available at: https://github.com/features/copilot

---
Project home: https://github.com/valorada/documentation
