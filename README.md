Bitcoin-ruby-node
This is a bitcoin node based on bitcoin-ruby-blockchain, that is capable of connecting to the bitcoin network, download and store the blockchain, validate all the blocks and incoming transactions, and relay data to its peers.

It also has a separate {Bitcoin::Node::CommandHandler CommandHandler} socket that can be used to query statistics, receive blockchain updates, relay transactions via the node, etc.

Installation

We assume you already have a ruby 1.9 or 2.0 compatible interpreter and rubygems environment.

gem install bitcoin-ruby-node
bitcoin_node --help
Or add it to your Gemfile and

require 'bitcoin/node'
