# Websearch

Search with your preferred search-engine. You can configure multiple engines.

## Usage

Enter your search-term and select the resulting search action you want to perform.

## Configuration

Default config

```
Config(
  prefix: "?",
  // Options: Google, Ecosia, Bing, DuckDuckGo, Custom
  //
  // Custom engines can be defined as such:
  // Custom(
  //   name: "Searx",
  //   url: "searx.be/?q={}",
  // )
  //
  // NOTE: `{}` is replaced by the search query and `https://` is automatically added in front.
  engines: [Google]
  // NOTE: Engines are comma delimited, e.g. "engines: [Google,Bing,Ecosia]". Search engine options will be ordered correspondingly in the GUI. 
)
```
