# Vibe4Gov - AI Coding Guidance for Government

Comprehensive guidance for using AI-assisted coding in government software development. This site provides the principles, processes, and tools needed to deliver secure, compliant, and maintainable government systems using modern AI coding practices.

## About Vibe4Gov

**Vibe coding** refers to the practice of using AI coding assistants effectively while maintaining the discipline, security, and compliance standards required for government systems. This guidance helps government development teams, contractors, and technical leadership adopt AI-assisted coding responsibly.

### Key Topics Covered

- **Introduction**: Understanding AI coding in government context
- **Core Principles**: Spec-first development, security by default, human oversight
- **Lifecycle**: From mission need to running system
- **Spec-Driven Development**: Government-ready specifications with AI assistance
- **Secure CI/CD**: Reference architectures and automated testing
- **Compliance**: OSCAL automation and continuous authorization
- **Reference Implementation**: Example application walkthrough
- **AI Tools**: Effective prompting and guardrails
- **Adoption**: Scaling across teams and agencies

## Quick Start

Visit the live site: [Vibe4Gov Guidance](https://vibe4gov.com/)

## Local Development

Pre-requisites: [Hugo](https://gohugo.io/getting-started/installing/), [Go](https://golang.org/doc/install) and [Git](https://git-scm.com)

```shell
# Clone the repo
git clone https://github.com/dlapiduz/vibe4gov.git

# Change directory
cd vibe4gov

# Start the server
hugo mod tidy
hugo server --logLevel debug --disableFastRender -p 1313
```

The site will be available at `http://localhost:1313/`

### Update theme

```shell
hugo mod get -u
hugo mod tidy
```

See [Update modules](https://gohugo.io/hugo-modules/use-modules/#update-modules) for more details.

## Contributing

This guidance is designed for government use cases with specific security and compliance requirements. Contributions should align with government development practices and regulatory frameworks.

## Built With

- [Hugo](https://gohugo.io/) - Static site generator
- [Hextra](https://github.com/imfing/hextra) - Documentation theme

## License

See [LICENSE](LICENSE) file for details.

