# CMU AI in a Human Society

Static site (Jekyll + Minima). Preview locally with either option below.

## Docker

Install [Docker Desktop](https://www.docker.com/products/docker-desktop/) and run it. From this folder:

```bash
docker compose up
```

Open http://localhost:4000. Stop with Ctrl+C.

## Ruby (macOS)

Install Ruby with Homebrew, then use Bundler in this folder:

```bash
brew install ruby
```

If `ruby --version` still shows the system Ruby, add Homebrew’s `export PATH=…` from the install “Caveats” to your shell config.

```bash
bundle install
bundle exec jekyll serve
```

Open http://127.0.0.1:4000 (Jekyll may print a slightly different URL).
