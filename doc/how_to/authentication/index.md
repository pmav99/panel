# Configuring Authentication

Authentication is a difficult topic fraught with potential pitfalls and complicated configuration options. Panel aims to be a "batteries-included" package for building applications and dashboards and therefore ships with a number of inbuilt providers for authentication in an application.

The primary mechanism by which Panel performs autentication is [OAuth 2.0](https://oauth.net/2/). The official specification for OAuth 2.0 describes the protocol as follows:

    The OAuth 2.0 authorization framework enables a third-party
    application to obtain limited access to an HTTP service, either on
    behalf of a resource owner by orchestrating an approval interaction
    between the resource owner and the HTTP service, or by allowing the
    third-party application to obtain access on its own behalf.

In other words OAuth outsources authentication to a third party provider, e.g. GitHub, Google or Azure AD, to authenticate the user credentials and give limited access to the APIs of that service.

::::{grid} 1 2 2 3
:gutter: 1 1 1 2

:::{grid-item-card} {octicon}`gear;2.5em;sd-mr-1` Configuring OAuth
:link: configuration
:link-type: doc

Discover how to configure OAuth from the commandline.
:::

:::{grid-item-card} {octicon}`shield;2.5em;sd-mr-1` OAuth Providers
:link: providers
:link-type: doc

A list of OAuth providers and how to configure them.
:::

:::{grid-item-card} {octicon}`shield-check;2.5em;sd-mr-1` User Information
:link: user_info
:link-type: doc

Discover how to make use of the user information and access tokens returned by the OAuth provider.
:::

::::

Note that since Panel is built on Bokeh server and Tornado it is also possible to implement your own authentication independent of the OAuth components shipped with Panel, [see the Bokeh documentation](https://docs.bokeh.org/en/latest/docs/user_guide/server.html#authentication) for further information.

```{toctree}
:titlesonly:
:hidden:
:maxdepth: 2

configuration
providers
user_info
```
