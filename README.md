# pulsar-mouse-noctalia

Standalone mirror of the `pulsar-mouse` Noctalia shell plugin, split out of
[pulsar-mouse-linux](https://github.com/harveywuk/pulsar-mouse-linux) (which
remains the source of truth for the driver/CLI/GUI) for two reasons:

- A backup independent of the monorepo.
- A clean source to copy from when submitting to
  [noctalia-dev/community-plugins](https://github.com/noctalia-dev/community-plugins),
  which expects each plugin as its own top-level directory with no unrelated
  driver code alongside it.

See [`pulsar-mouse/README.md`](pulsar-mouse/README.md) for the plugin itself.
This repo has no CI/build of its own - it's just files, kept manually in
sync with the plugin subtree in `pulsar-mouse-linux`.
