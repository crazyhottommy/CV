# CV

My CV template using pagedown.

Inside the `Rmd`:

```{css, echo=FALSE}
.pagedjs_page:not(:first-of-type) {
  background: white;
}
.pagedjs_page:not(:first-of-type) {
  --sidebar-width: 0rem;
  --sidebar-background-color: #ffffff;
  --main-width: calc(var(--content-width) - var(--sidebar-width));
  --decorator-horizontal-margin: 0.2in;
}
```

This trunk is to make only the first page has a side-bar and the rest of the page fill in the whole page.
see https://community.rstudio.com/t/pagedown-html-resume-with-aside-on-first-page-only/46351