# Backend Challenges boilerplate - package.json

--------------------------
## Notes:

__SemVer__ = Semantic Versioning

#### MAJOR.MINOR.PATCHES

Update Type | What it means
----------| -------------
__MAJOR__ | incompatible API changes, added changes that won't work with earlier versions
__MINOR__ | add functionality in a backwards-compatible manner, new features that won't break what worked before
__PATCH__ | backwards compatible bug fixes

### Tilde (~) vs Caret (^)

Tilde `~` allows npm to update the dependency's latest PATCH-version e.g.,

    "some-package-name": "~1.3.8"
npm updates this to any `1.3.x version`

Caret `^` allows npm to update the dependency's latest MINOR.PATCH-version e.g.,

    "some-package-name": "^1.3.8"
npm updates this to any `1.x.x version`