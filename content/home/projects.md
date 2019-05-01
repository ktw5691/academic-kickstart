+++
# Projects widget.
widget = "projects"
active = true
date = 2018-10-30T00:00:00

title = "Projects"
subtitle = ""

# Order that this section will appear in.
weight = 50

# Content.
# Display content from the following folder.
# For example, `folder = "project"` displays content from `content/project/`.
folder = "project"

# View.
# Customize how projects are displayed.
# List format.
#   1 = List
#   2 = Compact
#   3 = Card
#   4 = Citation (only available for publications)
#   5 = Showcase (large images, only available for projects)
view = 5

# Widget layout
# Legend: 0 = two columns (default), 1 = single column
widget_layout = 0

# For Showcase view, flip alternate rows?
flip_alt_rows = false

# Filter toolbar.

# Default filter index (e.g. 0 corresponds to the first `[[filter]]` instance below).
filter_default = 0

# Add or remove as many filters (`[[filter]]` instances) as you like.
# To show all items, set `tag` to "*".
# To filter by a specific tag, set `tag` to an existing tag name.
# To remove toolbar, delete/comment all instances of `[[filter]]` below.
[[filter]]
  name = "All"
  tag = "*"

[[filter]]
  name = "Topic Modeling"
  tag = ".topic-model"

[[filter]]
  name = "Comparative Cognition and Perception"
  tag = ".comparative-cognition"

+++
