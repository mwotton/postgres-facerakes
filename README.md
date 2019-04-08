# postgres-facerakes

PostgreSQL is a fabulous, industrial strength database, but it has
some somewhat unexpected behaviours. This repository aims to capture
and explain some of them, along with a quick demonstration of some
nifty features. (The presentation is in Haskell but most of these are
not Haskell-specific problems.)

## facerakes

### SQL null is not Maybe/Nullable/Option
### null bytes in utf8
### unexpected behaviour at different serialisation levels
### aggregation behaviour over zero rows
### long-held transactions

## examples

### json_agg
### json search
### full text search
### triggers
### native IP address manipulation
### dates
