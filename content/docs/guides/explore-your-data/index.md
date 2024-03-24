---
title: "Explore Your Data"
description: "Understand your team's flow metrics."
summary: ""
date: 2023-09-07T16:04:48+02:00
lastmod: 2023-09-07T16:04:48+02:00
draft: false
menu:
  docs:
    parent: ""
    identifier: "explore-your-data"
weight: 820
toc: true
seo:
  # title: "" # custom title (optional)
  # description: "" # custom description (recommended)
  # canonical: "" # custom canonical URL (optional)
  # noindex: false # false (default) or true
---

From the projects index page you can see links to various reports which will help you understand your team's performance.

![Report links](report-links.png)

## Issues

This links to the browse issues feature, from which you can browse and search all issues.

![Report links](epic-list.png)

In addition to the expected attributes (status, assignee, issue type, etc.) there are a few additional features which are useful for drilling down into specific issues and epics.

### Issue Preview

To quickly inspect an issue, you can use the preview button:

![Issue preview icon](issue-preview-icon.png)

This will show a preview pane over the list, which will include details such as flow metrics and the transition timeline for that issue.

![Issue preview](issue-preview.png)

### Issue Flow Metrics

Jira Flow Metrics computes cycle times based on the specified cycle time policy. This metric (along with the computed started and completed dates) is shown in all issues list, on issue details pages, and in the issue preview panes.

![Report links](view-epic.png)

TODO: link to cycle time policies guide.

### Epic Timeline

Above the list of child issues in an epic (on both the details page, as in the above screenshot, and on the epic preview pane) there is a `timeline` link. Clicking this link shows a detailed timeline of all issues in the epic: when they transitioned between statuses, and when they were completed.

![Epic timeline](epic-timeline.png)

## Flow Metric Reports

The cycle time reports include:

1. Cycle time scatterplot. This shows the cycle times of issues completed in a given period against their completion date, as well as percentiles to indicate typical and worst cases.

2. Cycle time histogram. This visualises the cycle time distribution of issues completed in the specified time period with a Pareto chart.

3. Ageing WIP (work in progress) chart. This shows the current age of in progress issues relative to other issues completed in the specified time period.

### Cycle Times

### Throughput

### Work In Progress (WIP)

## Planning and Forecasting Reports

Time Spent

Forecasting
