# Always
- Docs improvements! See [`FEEDBACK.md`](./FEEDBACK.md) for specific points.
- Loading patterns and auxiliary component examples

# v1
- [ ] Elicit feedback and use cases for the public API
- [ ] Investigate container `<div>`
- [ ] Solidify `<noscript>` fallback

# Investigate
- [ ] Auto sizes (if not handled already by browser behaviour)
- [ ] cancel loading on componentWillUnmount

# Later
- [ ] abort loading if image leaves viewport and it has not loaded sufficiently
  - Likely a large change to how we do things
  - Possibly with using fetch and cancelling it
  - Probably a mess
