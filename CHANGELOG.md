# 1.3.2
- babel plugin build in

# 1.3.0
- feat: ssr support (tested in next.js)

# 1.2.3
- fix: useMediaQuery sometime not work
- fix: #3, write background-image in module style, background-image will not work.

# 1.2.2
- remove: remove offline style cache feat.
- fix: StyleSheetsManager remove style from library accidentally.

# 1.2.1
- fix: useModule compile the source without module name after resize window
- fix: resize window createModuleStyle don't reset

# 1.2.0
- refactor: change `MediaQuery.XS` series toString result
- feat: add `MediaQuery.range` api

# 1.1.5
- fix: dynamic px not recount when window resize
- feat: release memory when no one use style

# 1.1.4
- support unit less like react style
- support dynamic px
- ignore illegal css rule

# 1.1.3
- add createModuleStyle api
- add palette api

# 1.1.0
- use stylis as the css preprocessor
- remove if scope support (stylis don't support this grammar)
- support @keyframes, browser prefix and so on which support in stylis
- add css api
- add useGlobalStyle api
- add useModuleStyle api
- rpx unit compile

# 1.0.4
- cache compile, store the code which have compiled but not use now.
- fix bug: can't work in safair.

# 1.0.3
- add style sheets elemtnt a id [style- hook]
- @media query support

# 1.0.2
fix bug: className may start with number make the style don't work.

# 1.0.0
initial release v1.0.0
