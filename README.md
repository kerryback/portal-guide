# Rice Business Data Portal Guide

Documentation site for the Rice University Business School Stock Market Data Portal.

## Overview

This repository contains the Quarto-based documentation for the [Rice Business Data Portal](https://data-portal.rice-business.org), providing comprehensive guides and examples for accessing and analyzing financial market data.

## Contents

- **User Guide** - Complete documentation for portal usage
- **API Examples** - Code samples and tutorials
- **Technical Documentation** - Integration guides and specifications

## Development

### Prerequisites
- [Quarto](https://quarto.org/docs/get-started/)
- R or Python (for code execution)

### Local Development
```bash
# Clone the repository
git clone https://github.com/kerryback/portal-guide.git
cd portal-guide

# Preview the site
quarto preview

# Build the site
quarto render
```

### Deployment
The site is automatically deployed to GitHub Pages from the `docs/` folder when changes are pushed to the main branch.

## Structure

```
portal-guide/
├── _quarto.yml           # Quarto configuration
├── index.qmd             # Home page
├── portal-user-guide.qmd # Main user guide
├── styles.css            # Custom styling
└── docs/                 # Generated output (GitHub Pages)
```

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test locally with `quarto preview`
5. Submit a pull request

## Links

- **Live Documentation**: [Portal Guide Site](https://kerryback.github.io/portal-guide/)
- **Data Portal**: [data-portal.rice-business.org](https://data-portal.rice-business.org)
- **Main Repository**: [github.com/kerryback/data_app](https://github.com/kerryback/data_app)
- **MCP Server**: [github.com/kerryback/mcp_server](https://github.com/kerryback/mcp_server)

## License

Documentation for the Rice University Business School Data Portal.

Developed by Kerry Back, J. Howard Creekmore Professor of Finance and Professor of Economics, Rice University Business School.