# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [0.2.0] - 2016-07-05
### Added
- Added `Lua.call_chunk!/3` and `Lua.call_function!/3`.
- Added `Lua.gc/1`.
- Added `Lua.load/2`, `Lua.load!/2`, `Lua.load_file/2`, `Lua.load_file!/2`.
- Added `Lua.set_table/3`.
- Added `Lua.State.wrap/1`, `Lua.State.unwrap/1`.

## 0.1.0 - 2016-07-04
### Added
- Initial release implementing `Lua.{eval,eval!,eval_file,eval_file!}/2`.

[Unreleased]: https://github.com/bendiken/exlua/compare/0.2.0...HEAD
[0.2.0]: https://github.com/bendiken/exlua/compare/0.1.0...0.2.0