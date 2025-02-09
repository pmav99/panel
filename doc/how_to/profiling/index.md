# Enable Profiling and Debugging

When trying to understand the performance profiles or track down issues with an application the server logs are rarely sufficient to gain insights. For that reason Panel ships with an admin dashboard that allows tracking resource usage, user behavior, and provides ways of visualizing profiling output to discover bottlenecks in an application.

::::{grid} 1 2 2 3
:gutter: 1 1 1 2

:::{grid-item-card} {octicon}`workflow;2.5em;sd-mr-1` Enable the admin panel
:link: admin
:link-type: doc
:class-title: sd-text-center

How to enable the admin Panel to begin monitoring resource usage and user behavior.
:::

:::{grid-item-card} {octicon}`workflow;2.5em;sd-mr-1` Profile your application
:link: profile
:link-type: doc
:class-title: sd-text-center

How to enable profilers like snakeviz or memray to track down bottlenecks in your application.
:::

:::{grid-item-card} {octicon}`workflow;2.5em;sd-mr-1` View application logs
:link: logs
:link-type: doc
:class-title: sd-text-center

How to view application logs in the admin dashboard.
:::

::::

```{toctree}
:titlesonly:
:hidden:
:maxdepth: 2

admin
profile
logs
```
