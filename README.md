Install *everything*
====================

This package requires the entirety of Hackage to be built.

-------------------------------------------------------------------------------

The joke started when a colleague liked the `leftToMaybe :: Either a b -> Maybe a`
function from `either`, which has a *huge* footprint compared to the utility it
provides.

This got us thinking about seemingly small packages that have lots of hidden
transitive dependencies, e.g. "only" `base`, `lens` and `yesod`. And that's
where `acme-everything` was born, which (transitively) depends on the entirety
of Hackage.
