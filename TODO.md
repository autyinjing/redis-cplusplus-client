
command handlers:
- support DEL as vararg
- support MLLEN and MSCARD
- support SDIFF
- support SDIFFSTORE

unit tests:
- sort with limit
- sort lexicographically
- sort with pattern and weights

extras:
- benchmarking "test" app
- consistent hashing?

maybe/someday:
- make all string literals constants so they can be easily changed
- add conveniences that store a std::set in its entirety (same for std::list, std::vector)
