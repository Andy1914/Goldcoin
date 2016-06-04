Goldcoin is a bitcoin node based application written in Ruby on Rails. Goldcoin is able connect to the bitcoin network, validate all the blocks and incoming transactions, and also is capable of downloading and storing the blockchain.


Installation

PS- You need to have ruby 1.9 or 2.0 compatible interpreter, and rubygems environment.

gem install bitcoin-ruby-node
bitcoin_node --help
Or add it to your Gemfile and

require 'bitcoin/node'
