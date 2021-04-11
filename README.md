# BELLATRIX-1
## PHASE 2 CHALLENGE 1

### CHALLENGE
- Curation: submit a post transaction with a content body
- Curation: upvote the above post
- Curation: upvote another validator's post
- Stake: stake on any post

### COMMANDS
- starsd tx curating post [vendor-id] [post-id] [body] [reward_address] --from [key] [flags]
(starsd tx curating post 1 "6475820" "from Ducca-StakeTab.com" stars18e9esk87ep9nnd8mc3m76q4lk5d6q7pnu4kxym --gas auto --fees 50000ustarx --from=ducca --chain-id="bellatrix-1")

- starsd tx curating upvote [vendor-id] [post-id] [voteNum] [reward-addr] --from [key] [flags]
(starsd tx curating upvote 1 "6475820" 1 stars18e9esk87ep9nnd8mc3m76q4lk5d6q7pnu4kxym --gas auto --fees 50000ustarx --from=ducca --chain-id="bellatrix-1")

- starsd tx curating upvote [vendor-id] [post-id] [voteNum] [reward-addr] --from [key] [flags]
(starsd tx curating upvote 0 "98" 1 stars18e9esk87ep9nnd8mc3m76q4lk5d6q7pnu4kxym --gas auto --fees 50000ustarx --from=ducca --chain-id="bellatrix-1")

- starsd tx stake stake [vendor-id] [post-id] [amount] [validator-address] --from [key] [flags]
(starsd tx stake stake 1 "666" 2000000 starsvaloper12xlxetf292m9llh5y9gwv92wkqwwagxulwl5l0 --gas auto --fees 50000ustarx --from=ducca --chain-id="bellatrix-1")

# DONE