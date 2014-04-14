rspec-smallspace-formatter
==========================

An RSpec formatter designed to be run in a small ( ~6 line) terminal

##Usage

With Rails

Add `small_space_formatter.rb` to the lib directory

Require the file in `spec_helper.rb`

```ruby
require 'small_space_formatter'
```

Run RSpec `rspec -f SmallSpaceFormatter`

If you are using Guard adjust your Guardfile to use the formatter

```ruby
guard :rspec, cmd: 'rspec -f SmallSpaceFormatter' do
```

