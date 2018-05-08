# Category of repos/specs

Note: one repo sometimes belongs to multiple categories.

## Bikeshed

* Normal Bikeshed spec with both `.bs` and `.html` in the default branch
* Bikeshed spec that contains only `.bs` file in `master`, and deploys the generated spec to `gh-pages` (example: Indexed DB)
* A repository containing multiple Bikeshed specs (example: Service Worker)
* Bikeshed spec that does not use GitHub Pages (example: CSS)

## ReSpec

* Normal ReSpec spec
* A repository containing multiple ReSpec specs (example: WCAG 2.1)
* ReSpec spec that deploys the generated spec (using [Spec Generator](https://github.com/w3c/spec-generator)) to `gh-pages` (example: WAI-ARIA)

# Supported GitHub orgs

* w3c
* WICG
* w3ctag

Considering:

* immersive-web
* WebBluetoothCG

# Things to do

* Add a feature to Bikeshed/ReSpec that can provide the URL of the current version of the spec