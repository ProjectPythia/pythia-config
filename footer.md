% This defines the footer of the site, and is not parsed as a regular "page"
% We point to it with the following in `myst.yml`:
% site:
%   parts:
%     footer: footer.md

% Here we use `grid` to add a basic grid structure to the HTML,
% but the formatting column sizes are defined manually in css/footer.css
% see the `grid-template-columns` line.
:::::{grid} 3
:class: items-center


```{image} logos/NSF-NCAR.png
:alt: NCAR Logo
```

```{image} logos/NSF-Unidata.png
:alt: Unidata Logo
```

```{image} logos/UAlbany.svg
:alt: UAlbany Logo
```
:::::


:::::{div}
:class: flex items-center gap-4

```{image} logos/nsf.jpg
:alt: NSF Logo
:height: 60px
```

<span style="font-size: 0.9em; line-height: 1.4;">
  This material is based upon work supported by the National Science Foundation under Grant Nos. 2026863 and 2026899. Any opinions, findings, and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the National Science Foundation.
</span>
:::::