# Installation

## Mac
I use mac, so `homebrew` makes it easy:

```
brew install go
```

### Other
I have come across `gvm`: Go Version Manager, and I use it at work.

## Tooling
* `go build` : compiler
* `go fmt` : formatter
* `go mod` : package manager
* `go test` : test runner
* `go vet` : scans for common mistakes! pretty cool.


## cli commands

#### `init`
`go mod init <module name>`

#### `get`
`go get <thing>`

#### `tidy`
`go mod tidy`

This is pretty useful!

#### `build`
`go build -o <name>`

build with a name!

#### `fmt`
`go fmt`

Interesting. I like that go defines a **standard** way of formatting. In my opinion, way better than the Javascript ecosystem / workflow. There might not need to be a specific step in a CICD pipeline to see if the code is formatted, or battling `eslint` and `prettier` settings. I have read a lot about how `golang` was designed to be easily parsed, and i think that standard formatting woud probably be helpful. It would probably make it faster to parse as well.

#### `vet`

`go vet`

I haven't come across this. Does `gopls` not complain about these sorts of errors? Maybe not. Nonetheless, seems like a really easy way to catch the low hanging fruit bugs. Very nice to have.

#### Choosing your tools

I currently use VSCode, but starting to dabble in nvim. I have to tooling set up in both.

# chapter thoughts

* it's nice to have a refresher with golang.
* some things i knew, a lot i did not.
