+++
# Projects widget.
# Note: this widget will only display if `content/project/` contains projects.

date = "2016-04-20T00:00:00"
draft = false

title = "项目"
subtitle = ""
widget = "projects"

# Order that this section will appear in.
weight = 50

# View.
# Customize how projects are displayed.
# Legend: 0 = list, 1 = cards.
view = 1

# Filter toolbar.
# Add or remove as many filters (`[[filter]]` instances) as you like.
# Use "*" tag to show all projects or an existing tag prefixed with "." to filter by specific tag.
# To remove toolbar, delete/comment all instances of `[[filter]]` below.
[[filter]]
  name = "全部"
  tag = "*"

[[filter]]
    name = "iOS"
    tag = ".ios"

[[filter]]
    name = "Android"
    tag = ".android"

[[filter]]
    name = "React Native"
    tag = ".react-native"

+++
