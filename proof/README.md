# ByeClaude public CI evidence

Separate account, same maintainer; CI evidence, not a third-party audit.

Commit: `dbe0720ff2a4f6546c8a6bacefe9e19c5662507f` · [Run 38060343437, attempt 1](https://github.com/angusu-de/ByeClaude/actions/runs/38060343437)

**10/10 jobs passed.** Overall workflow: `success`.

This snapshot describes the linked commit. Check the commit before relying on it for a newer checkout.

[Machine-readable evidence](public-proof.json)

## Go ubuntu-latest

Result: `success`

- Set up job: `success`
- Run actions/checkout@3d3c42e5aac5ba805825da76410c181273ba90b1: `success`
- Prebuilt action on this platform: `success`
- Run actions/setup-go@b7ad1dad31e06c5925ef5d2fc7ad053ef454303e: `success`
- Run go test ./...: `success`
- Run go vet ./...: `success`
- Run go build -trimpath ./cmd/byeclaude: `success`
- Native Windows hooks and recovery: `skipped`
- Post Run actions/setup-go@b7ad1dad31e06c5925ef5d2fc7ad053ef454303e: `success`
- Post Run actions/checkout@3d3c42e5aac5ba805825da76410c181273ba90b1: `success`
- Complete job: `success`

## Go windows-latest

Result: `success`

- Set up job: `success`
- Run actions/checkout@3d3c42e5aac5ba805825da76410c181273ba90b1: `success`
- Prebuilt action on this platform: `success`
- Run actions/setup-go@b7ad1dad31e06c5925ef5d2fc7ad053ef454303e: `success`
- Run go test ./...: `success`
- Run go vet ./...: `success`
- Run go build -trimpath ./cmd/byeclaude: `success`
- Native Windows hooks and recovery: `success`
- Post Run actions/setup-go@b7ad1dad31e06c5925ef5d2fc7ad053ef454303e: `success`
- Post Run actions/checkout@3d3c42e5aac5ba805825da76410c181273ba90b1: `success`
- Complete job: `success`

## Go macos-latest

Result: `success`

- Set up job: `success`
- Run actions/checkout@3d3c42e5aac5ba805825da76410c181273ba90b1: `success`
- Prebuilt action on this platform: `success`
- Run actions/setup-go@b7ad1dad31e06c5925ef5d2fc7ad053ef454303e: `success`
- Run go test ./...: `success`
- Run go vet ./...: `success`
- Run go build -trimpath ./cmd/byeclaude: `success`
- Native Windows hooks and recovery: `skipped`
- Post Run actions/setup-go@b7ad1dad31e06c5925ef5d2fc7ad053ef454303e: `success`
- Post Run actions/checkout@3d3c42e5aac5ba805825da76410c181273ba90b1: `success`
- Complete job: `success`

## Race, coverage and fixtures

Result: `success`

- Set up job: `success`
- Run actions/checkout@3d3c42e5aac5ba805825da76410c181273ba90b1: `success`
- Run actions/setup-go@b7ad1dad31e06c5925ef5d2fc7ad053ef454303e: `success`
- Formatting: `success`
- Module integrity: `success`
- Workflow syntax and semantics: `success`
- CI proof evidence tests: `success`
- Race detector: `success`
- Terminal input fuzzing: `success`
- Coverage floor: `success`
- Disposable fixture suite: `success`
- Self attribution guard: `success`
- Post Run actions/setup-go@b7ad1dad31e06c5925ef5d2fc7ad053ef454303e: `success`
- Post Run actions/checkout@3d3c42e5aac5ba805825da76410c181273ba90b1: `success`
- Complete job: `success`

## Dependency and static security gates

Result: `success`

- Set up job: `success`
- Run actions/checkout@3d3c42e5aac5ba805825da76410c181273ba90b1: `success`
- Run actions/setup-go@b7ad1dad31e06c5925ef5d2fc7ad053ef454303e: `success`
- Run go run golang.org/x/vuln/cmd/govulncheck@v1.8.0 ./...: `success`
- Run go run github.com/securego/gosec/v2/cmd/gosec@7b1b5cebe007d62fb58eacb90fc571112939ec30 -exclude-generated ./...: `success`
- Post Run actions/setup-go@b7ad1dad31e06c5925ef5d2fc7ad053ef454303e: `success`
- Post Run actions/checkout@3d3c42e5aac5ba805825da76410c181273ba90b1: `success`
- Complete job: `success`

## Shell installer

Result: `success`

- Set up job: `success`
- Run actions/checkout@3d3c42e5aac5ba805825da76410c181273ba90b1: `success`
- Run actions/setup-go@b7ad1dad31e06c5925ef5d2fc7ad053ef454303e: `success`
- Run bash scripts/test-install-shell.sh: `success`
- Post Run actions/setup-go@b7ad1dad31e06c5925ef5d2fc7ad053ef454303e: `success`
- Post Run actions/checkout@3d3c42e5aac5ba805825da76410c181273ba90b1: `success`
- Complete job: `success`

## PowerShell installer

Result: `success`

- Set up job: `success`
- Run actions/checkout@3d3c42e5aac5ba805825da76410c181273ba90b1: `success`
- Run actions/setup-go@b7ad1dad31e06c5925ef5d2fc7ad053ef454303e: `success`
- Run pwsh -NoProfile -File scripts/test-install-powershell.ps1: `success`
- Post Run actions/setup-go@b7ad1dad31e06c5925ef5d2fc7ad053ef454303e: `success`
- Post Run actions/checkout@3d3c42e5aac5ba805825da76410c181273ba90b1: `success`
- Complete job: `success`

## Reproducible release set and SBOM

Result: `success`

- Set up job: `success`
- Run actions/checkout@3d3c42e5aac5ba805825da76410c181273ba90b1: `success`
- Run actions/setup-go@b7ad1dad31e06c5925ef5d2fc7ad053ef454303e: `success`
- Run pwsh -NoProfile -File scripts/test-release-reproducibility.ps1: `success`
- Post Run actions/setup-go@b7ad1dad31e06c5925ef5d2fc7ad053ef454303e: `success`
- Post Run actions/checkout@3d3c42e5aac5ba805825da76410c181273ba90b1: `success`
- Complete job: `success`

## Demo container health

Result: `success`

- Set up job: `success`
- Run actions/checkout@3d3c42e5aac5ba805825da76410c181273ba90b1: `success`
- Build and probe non-root demo image: `success`
- Post Run actions/checkout@3d3c42e5aac5ba805825da76410c181273ba90b1: `success`
- Complete job: `success`

## Composite action self-test

Result: `success`

- Set up job: `success`
- Run actions/checkout@3d3c42e5aac5ba805825da76410c181273ba90b1: `success`
- Pinned binary, failure and argument-handling tests: `success`
- Old history and shallow checkout integration: `success`
- Run ./: `success`
- Post Run actions/checkout@3d3c42e5aac5ba805825da76410c181273ba90b1: `success`
- Complete job: `success`
