---
title: API Reference

language_tabs: # must be one of https://git.io/vQNgJ

  - python
  - r

# toc_footers:
#   - <a href='#'>Sign Up for a Developer Key</a>
#   - <a href='https://github.com/slatedocs/slate'>Documentation Powered by Slate</a>

includes:
  - van_data
  - census_data
  - fec_data
  - state_voter_file
  - state_shapefiles

search: true
---

# Introduction

Welcome to the Bluebonnet Data - Data Guide! This guide is designed to act as a compendium of every data source used by Bluebonnet teams, as well as a reference for teams looking for data sources or references on how to use them. Please update or add to this guide by suggesting edits! 

We have language bindings in R and Python! You can view code examples in the dark area to the right, and you can switch the programming language of the examples with the tabs in the top right.

This example API documentation page was created with [Slate](https://github.com/slatedocs/slate). Feel free to edit it and use it as a base for your own documentation.

# Tester Block -- Authentication

> To authorize, use this code:

```python
import kittn

api = kittn.authorize('meowmeowmeow')
```

```r 
library(kittn); 

api <- authorize('meowmeowmeow')
```

> Make sure to replace `meowmeowmeow` with your API key.

Kittn uses API keys to allow access to the API. You can register a new Kittn API key at our [developer portal](http://example.com/developers).

Kittn expects for the API key to be included in all API requests to the server in a header that looks like the following:

`Authorization: meowmeowmeow`

<aside class="notice">
You must replace <code>meowmeowmeow</code> with your personal API key.
</aside>

