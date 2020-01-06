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