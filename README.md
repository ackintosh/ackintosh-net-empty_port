# Ackintosh::Net::EmptyPort

Find a free TCP/UDP port.

## Installation

Add this line to your application's Gemfile:

    gem 'ackintosh-net-empty_port'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install ackintosh-net-empty_port

## Usage

### Find free TCP port

    port = Ackintosh::Net::EmptyPort.find

### Find free UDP port

    port = Ackintosh::Net::EmptyPort.find("udp")

### Check the given port is already used.

    Ackintosh::Net::EmptyPort.used?(80, "tcp")

also works for UDP.

### Author

Akihito Nakano

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
