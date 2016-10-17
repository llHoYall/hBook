# Control Statement

## `if` statement

```ruby
if condition
  statements
elsif condition
  statements
else
  statements
end

statement if condition
```
```ruby
x = 4
if x == 4
  puts 'This appears to be true.'
end

puts 'This appears to be true.' if not true    #false
puts 'This appears to be true.' if !true    # false
puts 'This appears to be true.' if 0    # true
puts 'This appears to be true.' if 1    # true
```

## `unless` statement

```ruby
unless condition
  statements
else
  statements
end

statement unless condition
```
```ruby
x = 4
unless x == 4
  puts 'This appears to be false.'
else
  puts 'This appears to be true.'
end

order.calculate_tax unless order.nil?
```

## `while` statement

```ruby
while condition
  statements
end

statement while condition
```
```ruby
x = 0
x = x + 1 while x < 10
```

## `until` statement

```ruby
statement until condition
```
```ruby
x = 10
x = x - 1 until x == 1
```

## `break` statement


