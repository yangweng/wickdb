## wickdb

[![Build Status](https://travis-ci.org/Fullstop000/wickdb.svg?branch=master)](https://travis-ci.org/Fullstop000/wickdb)
[![Coverage Status](https://coveralls.io/repos/github/Fullstop000/wickdb/badge.svg?branch=master)](https://coveralls.io/github/Fullstop000/wickdb?branch=master)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FFullstop000%2Fwickdb.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2FFullstop000%2Fwickdb?ref=badge_shield)

*This lib is in WIP and any current implementation may be unstable*

### Plan & Progress

##### [ongoing]The basic shape of LevelDB

- [ ] Fundamental components
  - [x] Arena
  - [x] Skiplist
  - [x] Cache
  - [x] Record
  - [x] Batch
  - [x] Block
  - [x] Table
  - [ ] Version
  - [x] VersionEdit
  - [ ] VersionSet
  - [x] Storage (aka Env)
  - [ ] DB
- [ ] Compaction implementation
- [ ] Scheduling
- [ ] Solid test cases
- [ ] Benchmark

##### Remove unsafe codes

We should use Rust as safe as we could because that's why we using Rust.

- `Slice` can be replaced using crate [bytes](https://docs.rs/bytes).
- `LRUCache` is a double-linked circle list implemented by raw pointer.


##### Add new features

TODO

## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FFullstop000%2Fwickdb.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FFullstop000%2Fwickdb?ref=badge_large)