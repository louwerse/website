+++
# Projects widget.
# This widget displays all projects from `content/project/`.

date = "2016-04-20T00:00:00"
draft = false

title = "Research Themes"
subtitle = ""
widget = "projects"

# Order that this section will appear in.
weight = 15

# Content.
# Display content from the following folder.
# For example, `folder = "project"` displays content from `content/project/`.
folder = "project"

# View.
# Customize how projects are displayed.
# Legend: 0 = list, 1 = cards, 2 = showcase.
view = 1

# Widget layout
# Legend: 0 = two columns (default), 1 = single column
widget_layout = 0


# For Showcase view, flip alternate rows?
flip_alt_rows = false

# Filter toolbar.

# Default filter index (e.g. 0 corresponds to the first `[[filter]]` instance below).
filter_default = 0

# Add or remove as many filters (`[[filter]]` instances) as you like.
# Use "*" tag to show all projects or an existing tag prefixed with "." to filter by specific tag.
# To remove toolbar, delete/comment all instances of `[[filter]]` below.
[[filter]]
  name = "All"
  tag = "*"
  
[[filter]]
  name = "Parliaments"
  tag = "parliaments"

[[filter]]
  name = "Elections"
  tag = "elections"

[[filter]]
  name = "Methodology"
  tag = "methodology"
  
+++

