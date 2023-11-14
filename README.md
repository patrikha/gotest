# Simple test projet
Folowing code will not work with Coverity 2023.6.1

## commands
```
~/cov-analysis/bin/cov-configure --config cov-config.xml --template --go
~/cov-analysis/bin/cov-build --config cov-config.xml --dir cov-int go build ./cmd/gotest
```
